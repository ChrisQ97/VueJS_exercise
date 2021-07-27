<template>
<div>
    <div><h1> PRIMER TEMA</h1>   </div>
        <div class="my-image">
            <b-container class="bv-example-row">
                <b-row align-v="center">
                    <b-col>
                        
                        <div class="my-image">
                            <b-img src="https://comenzandodecero.com/wp-content/uploads/2018/04/ima_6.jpeg" fluid alt="Responsive image"></b-img>
                        </div>


                    </b-col>
                    <b-col>

                        <div> <h3>Progressive Web apps</h3> </div>
                        <div>
                            <p>
                                Son aplicaciones Web que hacen uso de Service Workers, App shells y otras diversas tecnologias
                                para su funcionamiento, por lo general se considera que se comportan mas como aplicaciones que
                                como una aplicacion web, sin embargo estas siguen siendo accedidas mediante el navegador web.
                            </p>
                            <p>
                                A pesar de que se acceden mediante el navegador web estas cuentan con la opccion de que pueden
                                instalarse para ser utilizadas de manera offline.
                            </p>
                            <h4>Service Workers</h4>
                            <p> Permiten a los navegadores ejecutar servicios en segundo plano</p>
                        </div>
                    </b-col>
                    <b-col>
                       <div> <h3>Las PWA ofrecen:</h3> </div>
                       <div>
                            <b-list-group>
                            <b-list-group-item>Progresividad</b-list-group-item>
                            <b-list-group-item active>Adaptabilidad</b-list-group-item>
                            <b-list-group-item>Fiabilidad</b-list-group-item>
                            <b-list-group-item active>Apariencia de una applicacion normal</b-list-group-item>
                            <b-list-group-item>Seguridad</b-list-group-item>
                            </b-list-group>
                       </div>
                    </b-col>
                </b-row>
            </b-container>
        </div>

</div>

</template>
<script>
export default {
    name: 'Firsttema'
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