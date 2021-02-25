<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        <input type="text" v-model="input">

                        <p>My input output: {{input}}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
          return {
              input: ''
          }
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
