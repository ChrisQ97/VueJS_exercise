<template>
<div>
    <div><h1> SEGUNDO TEMA</h1>   </div>
        <div class="my-image">
            <b-container class="bv-example-row">
                <b-row align-v="center">
                    <b-col>
                        <div> <h3>REST APIs</h3> </div>    
                        <div>   
                            <p>
                            Estas son interfaces que nos permiten comunicar distintos tipos de aplicaciones,
                            por ejemplo si nuestra aplicacion necesita desplegar informacion del clima, utilizamos
                            la API respectiva para comunicarnos a x servicio que nos proporcione la informacion 
                            del clima 
                            </p>
                            <p>
                                Las API REST hacen uso de los verbos HTTP: GET, POST, PUT, DELETE y PATCH.
                            </p>
                        </div>

                    </b-col>
                    <b-col>
                        <div class="my-image">
                            <b-img src="https://phpenthusiast.com/theme/assets/images/blog/what_is_rest_api.png" fluid alt="Responsive image"></b-img>
                        </div>


                    </b-col>
                    <b-col>
                       <div>
                            <p> Otros tipos de APIs utilizados son las RPC y SOAP</p>
                            <p> Dentro del uso de APIs necesitamos contaar con URIs ya que,
                                estas sirven para identificar distintas acciones que se realizan en las request
                            </p>
                            <p> Por ejemplo para manejar un login podemos tener una URI "/user/login"</p>
                       </div>
                    </b-col>
                </b-row>
            </b-container>
        </div>

</div>

</template>
<script>
export default {
    name: 'Secondtema'
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