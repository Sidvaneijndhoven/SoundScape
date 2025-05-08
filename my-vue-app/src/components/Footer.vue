<template>
    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6">
        <div class="max-w-screen-xl mx-auto text-center">
            <p>&copy; 2025 SoundScape. All Rights Reserved.</p>
            <div class="space-x-6 mt-4">
                <a href="#" class="text-gray-400 hover:text-white" @click=" WorkInProgress">Facebook</a>
                <a href="#" class="text-gray-400 hover:text-white" @click=" WorkInProgress">Twitter</a>
                <a href="#" class="text-gray-400 hover:text-white" @click=" WorkInProgress">Instagram</a>
            </div>
        </div>
    </footer>
</template>

<script setup>
import { useToast } from 'vue-toastification'

const toast = useToast()

function bookNow() {
  toast.success('✅ Booking added to profile! check your profile for more information')
}

function WorkInProgress() {
  toast.error('🚧 This is still in development!')
}
</script>