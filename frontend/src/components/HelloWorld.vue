<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
    <h2>{{ msg }}</h2>

    <div class="card">
        <button type="button" @click="count++">count is {{ count }}</button>
    </div>
    <n-space>
        <n-button>Default</n-button>
        <n-button type="tertiary"> Tertiary </n-button>
        <n-button type="primary"> Primary </n-button>
        <n-button type="info"> Info </n-button>
        <n-button type="success"> Success </n-button>
        <n-button type="warning"> Warning </n-button>
        <n-button type="error"> Error </n-button>
    </n-space>
    <br>
    <n-space>
        <n-button strong secondary> Default </n-button>
        <n-button strong secondary type="tertiary"> Tertiary </n-button>
        <n-button strong secondary type="primary"> Primary </n-button>
        <n-button strong secondary type="info"> Info </n-button>
        <n-button strong secondary type="success"> Success </n-button>
        <n-button strong secondary type="warning"> Warning </n-button>
        <n-button strong secondary type="error"> Error </n-button>
    </n-space>
    <br>
    <n-space>
        <n-button strong secondary round> Default </n-button>
        <n-button strong secondary round type="primary"> Primary </n-button>
        <n-button strong secondary round type="info"> Info </n-button>
        <n-button strong secondary round type="success"> Success </n-button>
        <n-button strong secondary round type="warning"> Warning </n-button>
        <n-button strong secondary round type="error"> Error </n-button>
    </n-space>
    <br>
    <n-space>
        <n-button strong secondary circle>
            <template #icon>
                <n-icon><cash-icon /></n-icon>
            </template>
        </n-button>
        <n-button strong secondary circle type="primary">
            <template #icon>
                <n-icon><cash-icon /></n-icon>
            </template>
        </n-button>
        <n-button strong secondary circle type="info">
            <template #icon>
                <n-icon><cash-icon /></n-icon>
            </template>
        </n-button>
        <n-button strong secondary circle type="success">
            <template #icon>
                <n-icon><cash-icon /></n-icon>
            </template>
        </n-button>
        <n-button strong secondary circle type="warning">
            <template #icon>
                <n-icon><cash-icon /></n-icon>
            </template>
        </n-button>
        <n-button strong secondary circle type="error">
            <template #icon>
                <n-icon><cash-icon /></n-icon>
            </template>
        </n-button>
    </n-space>
</template>
<script lang="ts">
import { CashOutline as CashIcon } from '@vicons/ionicons5'
import { defineComponent } from 'vue'

export default defineComponent({
  components: {
    CashIcon
  }
})
</script>
<style scoped>
.read-the-docs {
    color: #888;
}
</style>
