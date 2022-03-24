<template>
    <app-layout title="Nuevo Usuario">
        <div class="card">
            <div class="card-header bg-primary text-white">
                <strong>NUEVO USUARIO</strong>
            </div>
            <div class="card-body">
                <div class="mb-3">
                    <label for="name" class="form-label">Nombre</label>
                    <input type="text" class="form-control" id="name" name="name">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" name="email">
                     <label for="password" class="form-label">Contraseña</label>
                    <input type="password" class="form-control" id="password"  name="password">
                     <label for="password_confirm" class="form-label">Confirmar Contraseña</label>
                    <input type="password" class="form-control" id="password_confirm" name="password_confirm">
                </div>
            </div>
            <div class="card-footer">
                <div class="d-grid gap-2">
                    <button type="submit" class="btn btn-primary text-white"><strong>GUARDAR</strong></button>
                </div>
            </div>
        </div>
    </app-layout>
</template>

<script>
import AppLayout from '@/Layouts/AppLayout.vue';
export default {
    components: {
        AppLayout
    },
    setup() {

    },
}
</script>
