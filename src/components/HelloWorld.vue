<template>
    <HelloWorld />
    <div class="container">
        <h2>Nuevo Componente</h2>
        <div class="row">
            <div class="card">
                <div class="card-body">
                    <span class="display-3">Contador : {{ this.numero }}</span>
                    <div class="row">
                        <button class="btn btn-success m-1" @click="%event => incrementar()">Incrementar</button>
                        <button class="btn btn-success m-1" @click="%event => decrementar()">Decrementar</button>
                    </div>
                </div>
            </div>
        </div>
        
    </div>    
</template>

<script>
export default {
  name: 'HelloWorld',
  data: function(){
    return{
        numero: 0
    }
  },
  methods: {
    incrementar() {
        this.numero = this.numero + 1
    },
    decrementar() {
        this.numero = this.numero - 1
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
