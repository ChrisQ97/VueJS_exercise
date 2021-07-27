<template>
<div>
    <div><h1> TERCER TEMA</h1>   </div>
        <div class="my-image">
            <b-container class="bv-example-row">
                <b-row align-v="center">
                    <b-col>
                        <div> <h3>Tecnologias Front End</h3> </div>    
                        <div>   
                            <div> <h4>CSS</h4></div>
                            <p>
                                Es un lenguaje de hojas de cascada, este se utiliza para dar estilo a los componentes HTML
                            </p>
                            <div> <h4>HTML</h4></div>
                            <p>
                                Es un lenguaje de maquetado utilizado para dar forma a las paginas web, es un lenguaje de maquetado, mas no de programacion
                            </p>
                        </div>

                    </b-col>
                    <b-col>
                       <div>
                            <div> <h4>Javascript</h4></div>
                            <p> Es un lenguaje interpretado, el cual se utiliza para gestionar acciones dentro del Desarrollo de Front End
                            </p>
                            
                       </div>


                    </b-col>
                    <b-col>
                        <div class="my-image">
                            <b-img src="https://www.datocms-assets.com/14946/1590690690-front-end.jpg" fluid alt="Responsive image"></b-img>
                        </div>


                    </b-col>
                </b-row>
            </b-container>
        </div>

</div>

</template>
<script>
export default {
    name: 'Tercertema'
}
</script>
<style scoped>
div{
    margin-top: 10px;
}
.my-image{
    display: flex;
    align-items: center;
    }
</style>