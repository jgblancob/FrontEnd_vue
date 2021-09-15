<template>
    <div class="row justify-content-center"> 
        <div class="col-md-6"> 
        <h3 class="text-center">Agregar contacto</h3>
        <form @submit.prevent="handleSubmitForm"> 
            <div class="form-group">
                <label>Nombre</label>
                <input
                    type="text"
                    class="form-control"
                    v-model="student.name"
                    required
                />
            </div>

            <div class="form-group">
                <label>Apellido</label>
                <input
                    type="text"
                    class="form-control"
                    v-model="student.name"
                    required
                />
            </div>

            <div class="form-group">
                <label>Celular</label>
                <input
                    type="text"
                    class="form-control"
                    v-model="student.name"
                    required
                />
            </div>

            <div class="form-group">
                <label>Celular de contacto</label>
                <input
                    type="text"
                    class="form-control"
                    v-model="student.name"
                    required
                />
            </div>
            
            <div class="form-group">
                <label>Email</label>
                <input
                    type="email"
                    class="form-control"
                    v-model="student.email"
                    required
                />
            </div>
            
            <div class="form-group">
                <label>Direccion de contacto</label>
                <input
                    type="text"
                    class="form-control"
                    v-model="student.phone"
                    required
                />
            </div>
                
                <div class="form-group">
                    <button class="btn btn-danger btn-block">Create</button>
                </div>
            </form>
        </div>
    </div> 
</template> 
 
<script>
export default {
    data() {
        return {
            student: {
                name: "",
                email: "",
                phone: "",
            },
        };
    },
    methods: {
        handleSubmitForm() {},
    },
}; 
</script> 

