<script setup lang="ts">

</script>

<template>
    <div class="bg-[#002F34] p-5 flex items-center justify-between">
        <img class="w-[70px] h-[70px] rounded-full"
            src="https://www.shutterstock.com/image-vector/olx-group-logo-vector-warsaw-260nw-2413532751.jpg"
            alt="Error">

        <div class="flex items-center gap-2">
            <template>
                <UInput class="w-[600px] h-[30px]" color="green" variant="outline" placeholder="Search..." model-value="" />
            </template>

            <template>
  <UButton
    class="h-[30px]"
    icon="majesticons:search-line"
    size="sm"
    color="primary"
    variant="solid"
    label="Search"
    :trailing="false"
  />
</template>




        </div>

        
        <div class="flex items-center justify-between gap-7">
            <NuxtLink class="flex items-center gap-2" to="/">
                <UIcon name="majesticons:chat-2-line" class="w-5 h-5" />
                <h3>Messages</h3>
            </NuxtLink>

            <NuxtLink class="flex items-center gap-2" to="/">
                <UIcon name="majesticons:heart-line" class="w-5 h-5" />
            </NuxtLink>

            <NuxtLink class="flex items-center gap-2" to="/">
                <UIcon name="majesticons:user-line" class="w-5 h-5" />
                <h3>Your Profile</h3>
            </NuxtLink>
        </div>

    </div>
</template>