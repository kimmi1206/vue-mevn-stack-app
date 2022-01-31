<template>
    <!-- Main -->
    <main class="main d-flex justify-content-start" role="main" name="main">
        <div class="container-fluid">
            <section id="main-section">
                <div class="row">
                    <article class="col">

                        <!-- Main Content -->

                        <!--Aqui puedes colocar tu codigo html/boostrap de tu modulo -->

                        <div class="container-fluid">

                            <table class="table align-middle">

                                <h1 class="display-4"> Stock </h1>
                                <hr>

                                <!-- <h1 id="registrar"> Registrar Productos </h1> -->

                                
                                    <div class="row align-content-center">
                                        <div class="col-sm-3">
                                            <label for="codigo">Codigo</label>
                                        </div>
                                        <div class="col-sm-5">
                                            <input type="text" id="codigo" name="codigo" placeholder="Codigo">
                                        </div>
                                    </div>
                                    <div class="row align-items-center">
                                        <div class="col-sm-3">
                                            <label for="producto">Producto</label>
                                        </div>
                                        <div class="col-sm-5">
                                            <input type="text" id="producto" name="producto"
                                                placeholder="Nombre Producto">
                                        </div>
                                    </div>
                                    <div class="row align-items-center">
                                        <div class="col-sm-3">
                                            <label for="categoria">Categoria</label>
                                        </div>
                                        <div class="col-sm-5">
                                            <div class="d-inline-flex p-2">
                                                <select class="p-1" id="categoria" name="categoria">
                                                    <optgroup label="Alimentos">
                                                        <option value="Azucares">Azucares</option>
                                                        <option value="Condimentos">Condimentos</option>
                                                    </optgroup>
                                                    <optgroup label="Aseo">
                                                        <option value="ahogar">Aseo Hogar</option>
                                                        <option value="apersonal">Aseo Personal</option>
                                                    </optgroup>
                                                    <optgroup label="Bebidas">
                                                        <option value="alcoholicas">Bebidas alcoholicas
                                                        </option>
                                                        <option value="refrescantes">Bebidas Refrescantes
                                                        </option>
                                                    </optgroup>
                                                </select>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row align-items-center">
                                        <div class="col-sm-3">
                                            <label for="pUnitario">P. Unitario</label>
                                        </div>
                                        <div class="col-sm-5">
                                            <input type="text" id="pUnitario" name="pUnitario"
                                                placeholder="Precio Unitario">
                                        </div>
                                    </div>
                                    <div class="row align-items-center">
                                        <div class="col-sm-3">
                                            <label for="unidad">Unidades</label>
                                        </div>
                                        <div class="col-sm-5">
                                            <input type="text" id="unidad" name="unidad" placeholder="Unidades">
                                        </div>
                                    </div>
                                    <div class="row align-items-center">
                                        <div class="col-sm-3">
                                            <label for="mStock">Stock Min.</label>
                                        </div>
                                        <div class="col-sm-5">
                                            <input type="text" id="mStock" name="mStock" placeholder="Stock Minimo">
                                        </div>
                                    </div>
                                    <div class="row align-items-center">
                                        <div class="col-sm-3">
                                            <label for="fVenci">F. Vencim.</label>
                                        </div>
                                        <div class="col-sm-5">
                                            <input type="date" id="fVenci" name="fVenci"
                                                placeholder="Fecha de Vencimiento">
                                        </div>
                                    </div>
                                    <div class="row align-items-center">
                                        <div class="col-sm-12">
                                            <button type="button" class="btn btn-primary btn-lg">Ingresar
                                                producto</button>
                                        </div>
                                    </div>
                                
                                <hr />
                            </table>
                        </div>
                    </article>
                </div>
                <div class="row">
                    <article class="col">

                        <div class="container-fluid">

                            <p><br></p>
                            <h1> Stock Actual </h1>

                            <div class="row">
                                <div class="col">
                                    <form action="/form/submit" method="GET">
                                        <input type="text" placeholder="Buscar" aria-label="Buscar"
                                            aria-describedby="basic-addon2">
                                        <button class="btn btn-outline-secondary" type="button">Button</button>
                                    </form>
                                    <div class="col">
                                        <label for="categoria">Ordenar por categoria:</label>
                                        <select name="categorias" id="categoria">
                                            <optgroup label="Alimentos">
                                                <option value="Azucares">Azucares</option>
                                                <option value="Condimentos">Condimentos</option>
                                            </optgroup>
                                            <optgroup label="Aseo">
                                                <option value="ahogar">Aseo Hogar</option>
                                                <option value="apersonal">Aseo Personal</option>
                                            </optgroup>
                                            <optgroup label="Bebidas">
                                                <option value="alcoholicas">Bebidas alcoholicas</option>
                                                <option value="refrescantes">Bebidas Refrescantes</option>
                                            </optgroup>
                                        </select>
                                    </div>
                                    <p></p>
                                </div>
                            </div>

                            <div class="row">
                                <div class="col">
                                    <div class="table-responsive">
                                        <table class="table table-bordered">
                                            <thead class="thead-light">
                                                <tr>

                                                    <th scope="col">Fecha de Ingreso</th>

                                                    <th scope="col">Codigo</th>

                                                    <th scope="col">Producto</th>

                                                    <th scope="col">Cantidad</th>

                                                    <th scope="col">P.unitario</th>

                                                    <th scope="col">Stock Minimo</th>

                                                    <th scope="col">Fecha de Vencimiento</th>

                                                </tr>
                                            </thead>
                                            <tr>

                                                <td>02/04/2021</td>

                                                <td>A34568</td>

                                                <td>Aceite girasol 1000 ml</td>

                                                <td>2</td>

                                                <td>$24.000</td>

                                                <td>$28.000</td>

                                                <td>01/01/2022</td>

                                            </tr>

                                            <tr>

                                                <td>25/05/2021</td>

                                                <td>A56785</td>

                                                <td>Azucar morena 3kg</td>

                                                <td>4</td>

                                                <td>$8.000</td>

                                                <td>$10.500</td>
                                                <td>27/02/2022</td>
                                            </tr>
                                            <tr>
                                                <td>18/06/2021</td>
                                                <td>B75398</td>
                                                <td>Sal refisal 3kg</td>
                                                <td>3</td>
                                                <td>$6.500</td>
                                                <td>$7.300</td>
                                                <td>25/10/2022</td>
                                            </tr>
                                        </table>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- End Main Content -->
                    </article>
                </div>
            </section>
        </div>
    </main>
    <!-- End Main -->

</template>

<script>
// import Vista from "./Vista.vue";
export default {
// /* <!-- Aqui van Scripts VueJS --> */
}
</script>

<style>
    /* <!-- Aqui va CSS --> */
</style>