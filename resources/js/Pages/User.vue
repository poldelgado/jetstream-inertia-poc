<template>
    <app-layout>
        <div class="card">
            <div class="card-header bg-info">
                Hola Mundo!
            </div>
            <div class="card-body">
                <pre>
                    {{users}}
                </pre>
            </div>
        </div>
    </app-layout>
</template>

<script>
import { defineComponent } from "vue"
import AppLayout from "@/Layouts/AppLayout.vue"

export default {
    props: ['users'],
    components: {
        AppLayout,
    },
    setup() {

    },
}
</script>
