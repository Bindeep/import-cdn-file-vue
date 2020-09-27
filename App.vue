<template>
    <div id="app">
        <nav class="navbar navbar-default navbar-fixed-top">
            <div class="container">
                <!-- Brand and toggle get grouped for better mobile display -->
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse"
                            data-target="#bs-example-navbar-collapse-1">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                    <a class="navbar-brand" href="#">You Shop Name</a>
                </div>

                <!-- Collect the nav links, forms, and other content for toggling -->
                <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                    <ul class="nav navbar-nav">
                        <li class="active"><a href="#" class="btn" data-toggle="modal" data-target="#myModal2">Food
                            Addition
                            Button <span class="sr-only">(current)</span></a></li>

                    </ul>

                </div><!-- /.navbar-collapse -->
            </div><!-- /.container-fluid -->
        </nav>


        <div class="modal right fade" id="myModal2" tabindex="-1" role="dialog" aria-labelledby="myModalLabel2">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span
                    aria-hidden="true">&times;</span>
            </button>
            <div class="modal-dialog" role="document">
                <div class="modal-content">

                    <div class="modal-header">

                        <h4>Add Food Extras</h4>
                    </div>

                    <div class="modal-body">
                        <div class="container-fluid">
                            <div class="row bg-white">
                                <div class="col-md-9 col-sm-8 padd-0">
                                    <div class="veg-dtl">

                                        <div class="row bg-white">
                                            <div class="col-xs-2 padd-0">
                                                <ul class="nav nav-tabs tabs-left">
                                                    <li class="active mt-0"><a href="#ClientInfo"
                                                                               data-toggle="tab">Vegetable</a></li>
                                                    <li><a href="#tab2" data-toggle="tab">Salad</a></li>
                                                    <li><a href="#tab3" data-toggle="tab">Chicken</a></li>
                                                    <li><a href="#tab4" data-toggle="tab">Meat</a></li>
                                                    <li><a href="#tab5" data-toggle="tab">Sauces</a></li>
                                                    <li><a href="#tab6" data-toggle="tab">Else</a></li>
                                                </ul>
                                            </div>
                                            <div class="col-xs-10 padd-left0 animated">
                                                <!-- Tab panes -->
                                                <div class="tab-content">
                                                    <div class="tab-pane active" id="ClientInfo">
                                                        <div class="header">
                                                            <div class="selectall">
                                                                <input id="sub-content-block-102" type="checkbox"
                                                                       value="">
                                                                <label for="sub-content-block-102">Select All</label>
                                                            </div>
                                                        </div>
                                                        <div class="ctnt-bdy">
                                                            <div class="series-btn ">
                                                                <div class="row">

                                                                    <div class="col-md-3 padd-1">
                                                                        <div class="btn_check">
                                                                            <input type="checkbox" id="c1">
                                                                            <label class="btn btn-default" for="c1">
                                                                                Corn
                                                                            </label>
                                                                        </div>
                                                                    </div>
                                                                    <div class="col-md-3 padd-1">
                                                                        <div class="btn_check">
                                                                            <input type="checkbox" id="c2">
                                                                            <label class="btn btn-default" for="c2">
                                                                                Unions
                                                                            </label>
                                                                        </div>
                                                                    </div>
                                                                    <div class="col-md-3 padd-1">
                                                                        <div class="btn_check">
                                                                            <input type="checkbox" id="c3">
                                                                            <label class="btn btn-default" for="c3">
                                                                                Tomato
                                                                            </label>
                                                                        </div>
                                                                    </div>
                                                                    <div class="col-md-3 padd-1">
                                                                        <div class="btn_check">
                                                                            <input type="checkbox" id="c4">
                                                                            <label class="btn btn-default" for="c4">
                                                                                peppers
                                                                            </label>
                                                                        </div>
                                                                    </div>


                                                                    <div class="col-md-3 padd-1">
                                                                        <div class="btn_check">
                                                                            <input type="checkbox" id="c5" checked>
                                                                            <label class="btn btn-default" for="c5">
                                                                                Tomato
                                                                            </label>
                                                                        </div>
                                                                    </div>

                                                                    <div class="col-md-3 padd-1">
                                                                        <div class="btn_check">
                                                                            <input type="checkbox" id="c6" checked>
                                                                            <label class="btn btn-default" for="c6">
                                                                                olive
                                                                            </label>
                                                                        </div>
                                                                    </div>

                                                                    <div class="col-md-3 padd-1">
                                                                        <div class="btn_check">
                                                                            <input type="checkbox" id="c7" checked>
                                                                            <label class="btn btn-default" for="c7">
                                                                                Corn
                                                                            </label>
                                                                        </div>
                                                                    </div>

                                                                    <div class="col-md-3 padd-1">
                                                                        <div class="btn_check">
                                                                            <input type="checkbox" id="c8" checked>
                                                                            <label class="btn btn-default" for="c8">
                                                                                unions
                                                                            </label>
                                                                        </div>
                                                                    </div>


                                                                </div>
                                                            </div>

                                                            <!-- 2nd row -->
                                                            <div class="second-row">

                                                                <div class="row">
                                                                    <div class="col-md-3 padd-0">
                                                                        <div class="inside-box">
                                                                            <div class="amnt">
                                  <span class="input-group">
                                    <span class="input-group-addon">Pizza</span>
                                    <select name="amount1" class="form-control">
                                      <option value="0">max-item</option>
                                      <option value="1">1</option>
                                      <option value="2">2</option>
                                      <option value="3">3</option>
                                      <option value="4">4</option>
                                    </select>
                                  </span>
                                                                            </div>
                                                                        </div>
                                                                    </div>


                                                                    <div class="col-md-3 padd-0">

                                  <span class="size-input-span">
                                    <span>Medium</span>
                                    <input type="text" value="0.50">
                                  </span>
                                                                    </div>
                                                                    <div class="col-md-3 padd-0">

                                  <span class="size-input-span">
                                    <span>Large</span>
                                    <input type="text" value="0.50">
                                  </span>
                                                                    </div>
                                                                    <div class="col-md-3 padd-0">

                                  <span class="size-input-span">
                                    <span>X Large</span>
                                    <input type="text" value="0.50">
                                  </span>
                                                                    </div>
                                                                </div>


                                                                <div class="row  bdr-top">
                                                                    <div class="mt-10">
                                                                        <div class="col-md-3 padd-0">
                                                                            <div class="inside-box">
                                                                                <div class="amnt">
                                  <span class="input-group">
                                    <span class="input-group-addon">Salad</span>
                                    <select name="amount1" class="form-control">
                                      <option value="0">max-item</option>
                                      <option value="1">1</option>
                                      <option value="2">2</option>
                                      <option value="3">3</option>
                                      <option value="4">4</option>
                                    </select>
                                  </span>
                                                                                </div>
                                                                            </div>
                                                                        </div>


                                                                        <div class="col-md-3 padd-0">

                                  <span class="size-input-span">
                                    <span>Standard</span>
                                    <input type="text" value="0.50">
                                  </span>
                                                                        </div>
                                                                        <div class="col-md-3 padd-0">

                                  <span class="size-input-span">
                                    <span>Sport</span>
                                    <input type="text" value="0.50">
                                  </span>
                                                                        </div>
                                                                        <div class="col-md-3 padd-0">

                                  <span class="size-input-span">
                                    <span>Family</span>
                                    <input type="text" value="0.50">
                                  </span>
                                                                        </div>
                                                                    </div>
                                                                </div>


                                                                <!-- 3rd row -->
                                                                <div class="row  bdr-top">
                                                                    <div class="mt-10">
                                                                        <div class="col-md-3 padd-0">
                                                                            <div class="inside-box">
                                                                                <div class="amnt">
                                  <span class="input-group">
                                    <span class="input-group-addon">Baguette</span>
                                    <select name="amount1" class="form-control">
                                      <option value="0">max-item</option>
                                      <option value="1">1</option>
                                      <option value="2">2</option>
                                      <option value="3">3</option>
                                      <option value="4">4</option>
                                    </select>
                                  </span>
                                                                                </div>
                                                                            </div>
                                                                        </div>


                                                                        <div class="col-md-3 padd-0">

                                  <span class="size-input-span">
                                    <span>Single</span>
                                    <input type="text" value="0.50">
                                  </span>
                                                                        </div>
                                                                        <!--   <div class="col-md-3 padd-0">

                                      <span class="size-input-span">
                                        <span>Sport</span>
                                        <input type="text" value="0.50">
                                      </span>
                                    </div>
                                      <div class="col-md-3 padd-0">

                                      <span class="size-input-span">
                                        <span>Family</span>
                                        <input type="text" value="0.50">
                                      </span>
                                    </div> -->
                                                                    </div>
                                                                </div>


                                                                <div class="row  bdr-top">
                                                                    <div class="mt-10">

                                                                    </div>
                                                                </div>
                                                            </div>


                                                        </div>
                                                    </div>
                                                    <div class="tab-pane" id="tab2">Tab 2.</div>
                                                    <div class="tab-pane" id="tab3">Tab 3.</div>
                                                    <div class="tab-pane" id="tab4">Tab 4.</div>
                                                    <div class="tab-pane" id="tab5">Tab 5.</div>
                                                    <div class="tab-pane" id="tab6">Tab 6.</div>
                                                </div>
                                            </div>
                                            <div class="col-md-10 col-md-offset-2">
                                                <div class="inside-box">
                                                    <div class="sve">
                                                        <a href="#" class="btn btn-default pushme2">Save</a>
                                                    </div>
                                                </div>
                                            </div>

                                        </div>
                                    </div>
                                </div>
                                <div class="col-md-3 ">
                                    <div id="accordion" class="panel-group">
                                        <!-- 1st panel -->
                                        <div class="panel panel-default">
                                            <div class="panel-heading" role="tab" id="headingOne">
                                                <h4 class="panel-title">
                                                    <a role="button" data-toggle="collapse" data-parent="#accordion"
                                                       href="#collapseOne" aria-expanded="true"
                                                       aria-controls="collapseOne">
                                                        Available Option
                                                    </a>
                                                </h4>
                                            </div>
                                            <div id="collapseOne" class="panel-collapse collapse in" role="tabpanel"
                                                 aria-labelledby="headingOne">
                                                <div class="panel-body">
                                                    <div class="box-1">
                                                        <div class="avl-head">
                                                            <h3>Pizza</h3>
                                                        </div>

                                                        <div class="avl-sel">
                                                            <ul>
                                                                <li><p>Medium</p></li>
                                                                <li><p>Large</p></li>
                                                                <li><p>X large</p></li>
                                                            </ul>
                                                        </div>
                                                    </div>


                                                    <div class="box-1">
                                                        <div class="avl-head">
                                                            <h3>Salad</h3>
                                                        </div>

                                                        <div class="avl-sel">
                                                            <ul>
                                                                <li><p>Medium</p></li>
                                                                <li><p>Large</p></li>

                                                            </ul>
                                                        </div>
                                                    </div>


                                                    <div class="box-1">
                                                        <div class="avl-head">
                                                            <h3>Kebab</h3>
                                                        </div>

                                                        <div class="avl-sel">
                                                            <ul>
                                                                <li><p>Chicken</p></li>
                                                                <li><p>Lamb</p></li>

                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>


                                        <!-- 2nd panel -->

                                        <div class="panel sidebar">
                                            <div class="panel-heading">
                                                <div class="cat-one-title">
                                                    <a data-toggle="collapse" data-parent="#accordion" href="#collapse2"
                                                       class="collapsed" aria-expanded="false">Pizza</a>
                                                    <input id="cat-one-title3" type="checkbox" value="">
                                                    <label for="cat-one-title3" class="sid-check-all"></label>
                                                </div>
                                            </div>

                                            <div id="collapse2" class="panel-collapse collapse">
                                                <div class="cat-one-sub-block">
                                                    <div class="one-cat-sub-block-one">
                                                        <label>123.</label>
                                                        <input id="cat-one-sub-block13" type="checkbox" value="">
                                                        <label for="cat-one-sub-block13">Pizza Salami</label>

                                                    </div>
                                                    <div class="one-cat-sub-block-one">
                                                        <label>124.</label>
                                                        <input id="cat-one-sub-block14" type="checkbox" value="">
                                                        <label for="cat-one-sub-block14">Pizza Salami</label>

                                                    </div>
                                                    <div class="one-cat-sub-block-one">
                                                        <label>125.</label>
                                                        <input id="cat-one-sub-block15" type="checkbox" value="">
                                                        <label for="cat-one-sub-block15">Pizza Salami</label>
                                                        <div class="avl-sel">
                                                            <ul>
                                                                <li><p>Medium</p></li>
                                                                <li><p>Large</p></li>
                                                                <li><p>X large</p></li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <!-- 3rd panel -->
                                        <div class="panel sidebar">
                                            <div class="panel-heading">
                                                <div class="cat-one-title">
                                                    <a data-toggle="collapse" data-parent="#accordion" href="#collapse3"
                                                       class="collapsed" aria-expanded="false">Salad</a>
                                                    <input id="cat-one-title4" type="checkbox" value="">
                                                    <label for="cat-one-title4" class="sid-check-all"></label>
                                                </div>
                                            </div>

                                            <div id="collapse3" class="panel-collapse collapse">
                                                <div class="cat-one-sub-block">
                                                    <div class="one-cat-sub-block-one">
                                                        <label>123.</label>
                                                        <input id="cat-one-sub-block16" type="checkbox" value="">
                                                        <label for="cat-one-sub-block16">Pizza Salami</label>

                                                    </div>
                                                    <div class="one-cat-sub-block-one">
                                                        <label>124.</label>
                                                        <input id="cat-one-sub-block23" type="checkbox" value="">
                                                        <label for="cat-one-sub-block23">Pizza Salami</label>

                                                    </div>
                                                    <div class="one-cat-sub-block-one">
                                                        <label>125.</label>
                                                        <input id="cat-one-sub-block17" type="checkbox" value="">
                                                        <label for="cat-one-sub-block17">Pizza Salami</label>
                                                        <div class="avl-sel">
                                                            <ul>
                                                                <li><p>Medium</p></li>
                                                                <li><p>Large</p></li>
                                                                <li><p>X large</p></li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <!-- 4th panel -->
                                        <div class="panel sidebar">
                                            <div class="panel-heading">
                                                <div class="cat-one-title">
                                                    <a data-toggle="collapse" data-parent="#accordion" href="#collapse4"
                                                       class="collapsed" aria-expanded="false">Baguette</a>
                                                    <input id="cat-one-title5" type="checkbox" value="">
                                                    <label for="cat-one-title5" class="sid-check-all"></label>
                                                </div>
                                            </div>

                                            <div id="collapse4" class="panel-collapse collapse">
                                                <div class="cat-one-sub-block">
                                                    <div class="one-cat-sub-block-one">
                                                        <label>123.</label>
                                                        <input id="cat-one-sub-block18" type="checkbox" value="">
                                                        <label for="cat-one-sub-block18">Pizza Salami</label>

                                                    </div>
                                                    <div class="one-cat-sub-block-one">
                                                        <label>124.</label>
                                                        <input id="cat-one-sub-block19" type="checkbox" value="">
                                                        <label for="cat-one-sub-block19">Pizza Salami</label>

                                                    </div>
                                                    <div class="one-cat-sub-block-one">
                                                        <label>125.</label>
                                                        <input id="cat-one-sub-block20" type="checkbox" value="">
                                                        <label for="cat-one-sub-block20">Pizza Salami</label>
                                                        <div class="avl-sel">
                                                            <ul>
                                                                <li><p>Medium</p></li>
                                                                <li><p>Large</p></li>
                                                                <li><p>X large</p></li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>

                                        </div>

                                        <!-- 5th panel -->
                                        <div class="panel sidebar">
                                            <div class="panel-heading">
                                                <div class="cat-one-title">
                                                    <a data-toggle="collapse" data-parent="#accordion" href="#collapse5"
                                                       class="collapsed" aria-expanded="false">Burger</a>
                                                    <input id="cat-one-title6" type="checkbox" value="">
                                                    <label for="cat-one-title6" class="sid-check-all"></label>
                                                </div>
                                            </div>

                                            <div id="collapse5" class="panel-collapse collapse">
                                                <div class="cat-one-sub-block">
                                                    <div class="one-cat-sub-block-one">
                                                        <label>123.</label>
                                                        <input id="cat-one-sub-block21" type="checkbox" value="">
                                                        <label for="cat-one-sub-block21">Pizza Salami</label>

                                                    </div>
                                                    <div class="one-cat-sub-block-one">
                                                        <label>124.</label>
                                                        <input id="cat-one-sub-block22" type="checkbox" value="">
                                                        <label for="cat-one-sub-block22">Pizza Salami</label>

                                                    </div>
                                                    <div class="one-cat-sub-block-one">
                                                        <label>125.</label>
                                                        <input id="cat-one-sub-block23" type="checkbox" value="">
                                                        <label for="cat-one-sub-block23">Pizza Salami</label>
                                                        <div class="avl-sel">
                                                            <ul>
                                                                <li><p>Medium</p></li>
                                                                <li><p>Large</p></li>
                                                                <li><p>X large</p></li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div><!-- modal-content -->
            </div><!-- modal-dialog -->
        </div>
    </div>
</template>

<script>

    export default {
        name: 'App',
        mounted() {
            const bootstrapCss = document.createElement('link');
            bootstrapCss.setAttribute('rel', 'stylesheet');
            bootstrapCss.setAttribute('type', 'text/css');
            bootstrapCss.setAttribute('href', 'https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css')
            document.head.appendChild(bootstrapCss);

            const fontAwesomeMin = document.createElement('link');
            fontAwesomeMin.setAttribute('rel', 'stylesheet');
            fontAwesomeMin.setAttribute('type', 'text/css');
            fontAwesomeMin.setAttribute('href', 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.4.0/css/font-awesome.min.css')
            document.head.appendChild(fontAwesomeMin);

            const jqueryMin = document.createElement('script');
            jqueryMin.setAttribute('src', 'https://code.jquery.com/jquery-3.2.1.min.js')
            document.head.appendChild(jqueryMin);

            function addBootstrapMin() {
                const bootstrapMin = document.createElement('script');
                bootstrapMin.setAttribute('src', 'https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js')
                document.head.appendChild(bootstrapMin)
            }

            setTimeout(function () {
                addBootstrapMin();
            }, 300);
        }
    }
</script>

<style scoped>
    .animated {
        -webkit-animation-duration: 1s;
        animation-duration: 1s;
        -webkit-animation-fill-mode: both;
        animation-fill-mode: both
    }

    @-webkit-keyframes bounceIn {
        0% {
            opacity: 0;
            -webkit-transform: scale(.3)
        }
        50% {
            opacity: 1;
            -webkit-transform: scale(1.05)
        }
        70% {
            -webkit-transform: scale(.9)
        }
        100% {
            -webkit-transform: scale(1)
        }
    }

    @keyframes bounceIn {
        0% {
            opacity: 0;
            transform: scale(.3)
        }
        50% {
            opacity: 1;
            transform: scale(1.05)
        }
        70% {
            transform: scale(.9)
        }
        100% {
            transform: scale(1)
        }
    }

    @-webkit-keyframes bounceInRight {
        0% {
            opacity: 0;
            -webkit-transform: translateX(400px)
        }
        60% {
            -webkit-transform: translateX(-30px)
        }
        80% {
            -webkit-transform: translateX(10px)
        }
        100% {
            opacity: 1;
            -webkit-transform: translateX(0)
        }
    }

    @keyframes bounceInRight {
        0% {
            opacity: 0;
            transform: translateX(400px)
        }
        60% {
            transform: translateX(-30px)
        }
        80% {
            transform: translateX(10px)
        }
        100% {
            opacity: 1;
            transform: translateX(0)
        }
    }

    @-webkit-keyframes bounceInLeft {
        0% {
            opacity: 0;
            -webkit-transform: translateX(-400px)
        }
        60% {
            -webkit-transform: translateX(30px)
        }
        80% {
            -webkit-transform: translateX(-10px)
        }
        100% {
            opacity: 1;
            -webkit-transform: translateX(0)
        }
    }

    @keyframes bounceInLeft {
        0% {
            opacity: 0;
            transform: translateX(-400px)
        }
        60% {
            transform: translateX(30px)
        }
        80% {
            transform: translateX(-10px)
        }
        100% {
            opacity: 1;
            transform: translateX(0)
        }
    }

    @-webkit-keyframes bounceInUp {
        0% {
            opacity: 0;
            -webkit-transform: translateY(400px)
        }
        60% {
            -webkit-transform: translateY(-30px)
        }
        80% {
            -webkit-transform: translateY(10px)
        }
        100% {
            opacity: 1;
            -webkit-transform: translateY(0)
        }
    }

    @keyframes bounceInUp {
        0% {
            opacity: 0;
            transform: translateY(400px)
        }
        60% {
            transform: translateY(-30px)
        }
        80% {
            transform: translateY(10px)
        }
        100% {
            opacity: 1;
            transform: translateY(0)
        }
    }

    @-webkit-keyframes bounceInDown {
        0% {
            opacity: 0;
            -webkit-transform: translateY(-400px)
        }
        60% {
            -webkit-transform: translateY(30px)
        }
        80% {
            -webkit-transform: translateY(-10px)
        }
        100% {
            opacity: 1;
            -webkit-transform: translateY(0)
        }
    }

    @keyframes bounceInDown {
        0% {
            opacity: 0;
            transform: translateY(-400px)
        }
        60% {
            transform: translateY(30px)
        }
        80% {
            transform: translateY(-10px)
        }
        100% {
            opacity: 1;
            transform: translateY(0)
        }
    }

    @-webkit-keyframes fadeIn {
        0% {
            opacity: 0
        }
        100% {
            opacity: 1;
            display: block
        }
    }

    @keyframes fadeIn {
        0% {
            opacity: 0
        }
        100% {
            opacity: 1;
            display: block
        }
    }

    @-webkit-keyframes growIn {
        0% {
            -webkit-transform: scale(.2);
            opacity: 0
        }
        50% {
            -webkit-transform: scale(1.2)
        }
        100% {
            -webkit-transform: scale(1);
            opacity: 1
        }
    }

    @keyframes growIn {
        0% {
            transform: scale(.2);
            opacity: 0
        }
        50% {
            transform: scale(1.2)
        }
        100% {
            transform: scale(1);
            opacity: 1
        }
    }

    @-webkit-keyframes shake {
        0%, 100% {
            -webkit-transform: translateX(0)
        }
        10%, 30%, 50%, 70%, 90% {
            -webkit-transform: translateX(-10px)
        }
        20%, 40%, 60%, 80% {
            -webkit-transform: translateX(10px)
        }
    }

    @keyframes shake {
        0%, 100% {
            transform: translateX(0)
        }
        10%, 30%, 50%, 70%, 90% {
            transform: translateX(-10px)
        }
        20%, 40%, 60%, 80% {
            transform: translateX(10px)
        }
    }

    @-webkit-keyframes shakeUp {
        0%, 100% {
            -webkit-transform: translateX(0)
        }
        10%, 30%, 50%, 70%, 90% {
            -webkit-transform: translateY(-10px)
        }
        20%, 40%, 60%, 80% {
            -webkit-transform: translateY(10px)
        }
    }

    @keyframes shakeUp {
        0%, 100% {
            transform: translateY(0)
        }
        10%, 30%, 50%, 70%, 90% {
            transform: translateY(-10px)
        }
        20%, 40%, 60%, 80% {
            transform: translateY(10px)
        }
    }

    @-webkit-keyframes fadeInLeft {
        0% {
            opacity: 0;
            -webkit-transform: translateX(-400px)
        }
        50% {
            opacity: .3
        }
        100% {
            opacity: 1;
            -webkit-transform: translateX(0)
        }
    }

    @keyframes fadeInLeft {
        0% {
            opacity: 0;
            transform: translateX(-400px)
        }
        50% {
            opacity: .3
        }
        100% {
            opacity: 1;
            transform: translateX(0)
        }
    }

    @-webkit-keyframes fadeInRight {
        0% {
            opacity: 0;
            -webkit-transform: translateX(400px)
        }
        50% {
            opacity: .3
        }
        100% {
            opacity: 1;
            -webkit-transform: translateX(0)
        }
    }

    @keyframes fadeInRight {
        0% {
            opacity: 0;
            transform: translateX(400px)
        }
        50% {
            opacity: .3
        }
        100% {
            opacity: 1;
            transform: translateX(0)
        }
    }

    @-webkit-keyframes fadeInUp {
        0% {
            opacity: 0;
            -webkit-transform: translateY(400px)
        }
        50% {
            opacity: .3
        }
        100% {
            opacity: 1;
            -webkit-transform: translateY(0)
        }
    }

    @keyframes fadeInUp {
        0% {
            opacity: 0;
            transform: translateY(400px)
        }
        50% {
            opacity: .3
        }
        100% {
            opacity: 1;
            transform: translateY(0)
        }
    }

    @-webkit-keyframes fadeInDown {
        0% {
            opacity: 0;
            -webkit-transform: translateY(-400px)
        }
        50% {
            opacity: .3
        }
        100% {
            opacity: 1;
            -webkit-transform: translateY(0)
        }
    }

    @keyframes fadeInDown {
        0% {
            opacity: 0;
            transform: translateY(-400px)
        }
        50% {
            opacity: .3
        }
        100% {
            opacity: 1;
            transform: translateY(0)
        }
    }

    @-webkit-keyframes rotateIn {
        0% {
            -webkit-transform-origin: center center;
            -webkit-transform: rotate(-200deg);
            opacity: 0
        }
        100% {
            -webkit-transform-origin: center center;
            -webkit-transform: rotate(0);
            opacity: 1
        }
    }

    @keyframes rotateIn {
        0% {
            transform-origin: center center;
            transform: rotate(-200deg);
            opacity: 0
        }
        100% {
            transform-origin: center center;
            transform: rotate(0);
            opacity: 1
        }
    }

    @-webkit-keyframes rotateInUpLeft {
        0% {
            -webkit-transform-origin: left bottom;
            -webkit-transform: rotate(90deg);
            opacity: 0
        }
        100% {
            -webkit-transform-origin: left bottom;
            -webkit-transform: rotate(0);
            opacity: 1
        }
    }

    @keyframes rotateInUpLeft {
        0% {
            transform-origin: left bottom;
            transform: rotate(90deg);
            opacity: 0
        }
        100% {
            transform-origin: left bottom;
            transform: rotate(0);
            opacity: 1
        }
    }

    @-webkit-keyframes rotateInDownLeft {
        0% {
            -webkit-transform-origin: left bottom;
            -webkit-transform: rotate(-90deg);
            opacity: 0
        }
        100% {
            -webkit-transform-origin: left bottom;
            -webkit-transform: rotate(0);
            opacity: 1
        }
    }

    @keyframes rotateInDownLeft {
        0% {
            transform-origin: left bottom;
            transform: rotate(-90deg);
            opacity: 0
        }
        100% {
            transform-origin: left bottom;
            transform: rotate(0);
            opacity: 1
        }
    }

    @-webkit-keyframes rotateInUpRight {
        0% {
            -webkit-transform-origin: right bottom;
            -webkit-transform: rotate(-90deg);
            opacity: 0
        }
        100% {
            -webkit-transform-origin: right bottom;
            -webkit-transform: rotate(0);
            opacity: 1
        }
    }

    @keyframes rotateInUpRight {
        0% {
            transform-origin: right bottom;
            transform: rotate(-90deg);
            opacity: 0
        }
        100% {
            transform-origin: right bottom;
            transform: rotate(0);
            opacity: 1
        }
    }

    @-webkit-keyframes rotateInDownRight {
        0% {
            -webkit-transform-origin: right bottom;
            -webkit-transform: rotate(90deg);
            opacity: 0
        }
        100% {
            -webkit-transform-origin: right bottom;
            -webkit-transform: rotate(0);
            opacity: 1
        }
    }

    @keyframes rotateInDownRight {
        0% {
            transform-origin: right bottom;
            transform: rotate(90deg);
            opacity: 0
        }
        100% {
            transform-origin: right bottom;
            transform: rotate(0);
            opacity: 1
        }
    }

    @-webkit-keyframes rollIn {
        0% {
            opacity: 0;
            -webkit-transform: translateX(-100%) rotate(-120deg)
        }
        100% {
            opacity: 1;
            -webkit-transform: translateX(0) rotate(0)
        }
    }

    @keyframes rollIn {
        0% {
            opacity: 0;
            transform: translateX(-100%) rotate(-120deg)
        }
        100% {
            opacity: 1;
            transform: translateX(0) rotate(0)
        }
    }

    @-webkit-keyframes wiggle {
        0% {
            -webkit-transform: skewX(9deg)
        }
        10% {
            -webkit-transform: skewX(-8deg)
        }
        20% {
            -webkit-transform: skewX(7deg)
        }
        30% {
            -webkit-transform: skewX(-6deg)
        }
        40% {
            -webkit-transform: skewX(5deg)
        }
        50% {
            -webkit-transform: skewX(-4deg)
        }
        60% {
            -webkit-transform: skewX(3deg)
        }
        70% {
            -webkit-transform: skewX(-2deg)
        }
        80% {
            -webkit-transform: skewX(1deg)
        }
        100%, 90% {
            -webkit-transform: skewX(0)
        }
    }

    @keyframes wiggle {
        0% {
            transform: skewX(9deg)
        }
        10% {
            transform: skewX(-8deg)
        }
        20% {
            transform: skewX(7deg)
        }
        30% {
            transform: skewX(-6deg)
        }
        40% {
            transform: skewX(5deg)
        }
        50% {
            transform: skewX(-4deg)
        }
        60% {
            transform: skewX(3deg)
        }
        70% {
            transform: skewX(-2deg)
        }
        80% {
            transform: skewX(1deg)
        }
        100%, 90% {
            transform: skewX(0)
        }
    }

    @-webkit-keyframes swing {
        100%, 20%, 40%, 60%, 80% {
            -webkit-transform-origin: top center
        }
        20% {
            -webkit-transform: rotate(15deg)
        }
        40% {
            -webkit-transform: rotate(-10deg)
        }
        60% {
            -webkit-transform: rotate(5deg)
        }
        80% {
            -webkit-transform: rotate(-5deg)
        }
        100% {
            -webkit-transform: rotate(0)
        }
    }

    @keyframes swing {
        20% {
            transform: rotate(15deg)
        }
        40% {
            transform: rotate(-10deg)
        }
        60% {
            transform: rotate(5deg)
        }
        80% {
            transform: rotate(-5deg)
        }
        100% {
            transform: rotate(0)
        }
    }

    @-webkit-keyframes tada {
        0% {
            -webkit-transform: scale(1)
        }
        10%, 20% {
            -webkit-transform: scale(.9) rotate(-3deg)
        }
        30%, 50%, 70%, 90% {
            -webkit-transform: scale(1.1) rotate(3deg)
        }
        40%, 60%, 80% {
            -webkit-transform: scale(1.1) rotate(-3deg)
        }
        100% {
            -webkit-transform: scale(1) rotate(0)
        }
    }

    @keyframes tada {
        0% {
            transform: scale(1)
        }
        10%, 20% {
            transform: scale(.9) rotate(-3deg)
        }
        30%, 50%, 70%, 90% {
            transform: scale(1.1) rotate(3deg)
        }
        40%, 60%, 80% {
            transform: scale(1.1) rotate(-3deg)
        }
        100% {
            transform: scale(1) rotate(0)
        }
    }

    @-webkit-keyframes wobble {
        0%, 100% {
            -webkit-transform: translateX(0)
        }
        15% {
            -webkit-transform: translateX(-25%) rotate(-5deg)
        }
        30% {
            -webkit-transform: translateX(20%) rotate(3deg)
        }
        45% {
            -webkit-transform: translateX(-15%) rotate(-3deg)
        }
        60% {
            -webkit-transform: translateX(10%) rotate(2deg)
        }
        75% {
            -webkit-transform: translateX(-5%) rotate(-1deg)
        }
    }

    @keyframes wobble {
        0%, 100% {
            transform: translateX(0)
        }
        15% {
            transform: translateX(-25%) rotate(-5deg)
        }
        30% {
            transform: translateX(20%) rotate(3deg)
        }
        45% {
            transform: translateX(-15%) rotate(-3deg)
        }
        60% {
            transform: translateX(10%) rotate(2deg)
        }
        75% {
            transform: translateX(-5%) rotate(-1deg)
        }
    }


    @-webkit-keyframes pulse {
        0%, 100% {
            -webkit-transform: scale(1)
        }
        50% {
            -webkit-transform: scale(1.1)
        }
    }

    @keyframes pulse {
        0%, 100% {
            transform: scale(1)
        }
        50% {
            transform: scale(1.1)
        }
    }


    @-webkit-keyframes lightSpeedInRight {
        0% {
            -webkit-transform: translateX(100%) skewX(-30deg);
            opacity: 0
        }
        60% {
            -webkit-transform: translateX(-20%) skewX(30deg);
            opacity: 1
        }
        80% {
            -webkit-transform: translateX(0) skewX(-15deg);
            opacity: 1
        }
        100% {
            -webkit-transform: translateX(0) skewX(0);
            opacity: 1
        }
    }

    @keyframes lightSpeedInRight {
        0% {
            transform: translateX(100%) skewX(-30deg);
            opacity: 0
        }
        60% {
            transform: translateX(-20%) skewX(30deg);
            opacity: 1
        }
        80% {
            transform: translateX(0) skewX(-15deg);
            opacity: 1
        }
        100% {
            transform: translateX(0) skewX(0);
            opacity: 1
        }
    }


    @-webkit-keyframes lightSpeedInLeft {
        0% {
            -webkit-transform: translateX(-100%) skewX(30deg);
            opacity: 0
        }
        60% {
            -webkit-transform: translateX(20%) skewX(-30deg);
            opacity: 1
        }
        80% {
            -webkit-transform: translateX(0) skewX(15deg);
            opacity: 1
        }
        100% {
            -webkit-transform: translateX(0) skewX(0);
            opacity: 1
        }
    }

    @keyframes lightSpeedInLeft {
        0% {
            transform: translateX(-100%) skewX(30deg);
            opacity: 0
        }
        60% {
            transform: translateX(20%) skewX(-30deg);
            opacity: 1
        }
        80% {
            transform: translateX(0) skewX(15deg);
            opacity: 1
        }
        100% {
            transform: translateX(0) skewX(0);
            opacity: 1
        }
    }

    @-webkit-keyframes flip {
        0% {
            -webkit-transform: perspective(400px) rotateY(0);
            -webkit-animation-timing-function: ease-out
        }
        40% {
            -webkit-transform: perspective(400px) translateZ(150px) rotateY(170deg);
            -webkit-animation-timing-function: ease-out
        }
        50% {
            -webkit-transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
            -webkit-animation-timing-function: ease-in
        }
        80% {
            -webkit-transform: perspective(400px) rotateY(360deg) scale(.95);
            -webkit-animation-timing-function: ease-in
        }
        100% {
            -webkit-transform: perspective(400px) scale(1);
            -webkit-animation-timing-function: ease-in
        }
    }

    @keyframes flip {
        0% {
            transform: perspective(400px) rotateY(0);
            animation-timing-function: ease-out
        }
        40% {
            transform: perspective(400px) translateZ(150px) rotateY(170deg);
            animation-timing-function: ease-out
        }
        50% {
            transform: perspective(400px) translateZ(150px) rotateY(190deg) scale(1);
            animation-timing-function: ease-in
        }
        80% {
            transform: perspective(400px) rotateY(360deg) scale(.95);
            animation-timing-function: ease-in
        }
        100% {
            transform: perspective(400px) scale(1);
            animation-timing-function: ease-in
        }
    }

    @-webkit-keyframes flipInX {
        0% {
            -webkit-transform: perspective(400px) rotateX(90deg);
            opacity: 0
        }
        40% {
            -webkit-transform: perspective(400px) rotateX(-10deg)
        }
        70% {
            -webkit-transform: perspective(400px) rotateX(10deg)
        }
        100% {
            -webkit-transform: perspective(400px) rotateX(0);
            opacity: 1
        }
    }

    @keyframes flipInX {
        0% {
            transform: perspective(400px) rotateX(90deg);
            opacity: 0
        }
        40% {
            transform: perspective(400px) rotateX(-10deg)
        }
        70% {
            transform: perspective(400px) rotateX(10deg)
        }
        100% {
            transform: perspective(400px) rotateX(0);
            opacity: 1
        }
    }

    @-webkit-keyframes flipInY {
        0% {
            -webkit-transform: perspective(400px) rotateY(90deg);
            opacity: 0
        }
        40% {
            -webkit-transform: perspective(400px) rotateY(-10deg)
        }
        70% {
            -webkit-transform: perspective(400px) rotateY(10deg)
        }
        100% {
            -webkit-transform: perspective(400px) rotateY(0);
            opacity: 1
        }
    }

    @keyframes flipInY {
        0% {
            transform: perspective(400px) rotateY(90deg);
            opacity: 0
        }
        40% {
            transform: perspective(400px) rotateY(-10deg)
        }
        70% {
            transform: perspective(400px) rotateY(10deg)
        }
        100% {
            transform: perspective(400px) rotateY(0);
            opacity: 1
        }
    }

    @-webkit-keyframes bounceOut {
        0% {
            -webkit-transform: scale(1)
        }
        25% {
            -webkit-transform: scale(.95)
        }
        50% {
            opacity: 1;
            -webkit-transform: scale(1.1)
        }
        100% {
            opacity: 0;
            -webkit-transform: scale(.3)
        }
    }

    @keyframes bounceOut {
        0% {
            transform: scale(1)
        }
        25% {
            transform: scale(.95)
        }
        50% {
            opacity: 1;
            transform: scale(1.1)
        }
        100% {
            opacity: 0;
            transform: scale(.3)
        }
    }

    @-webkit-keyframes bounceOutUp {
        0% {
            -webkit-transform: translateY(0)
        }
        20% {
            opacity: 1;
            -webkit-transform: translateY(20px)
        }
        100% {
            opacity: 0;
            -webkit-transform: translateY(-2000px)
        }
    }

    @keyframes bounceOutUp {
        0% {
            transform: translateY(0)
        }
        20% {
            opacity: 1;
            transform: translateY(20px)
        }
        100% {
            opacity: 0;
            transform: translateY(-2000px)
        }
    }

    @-webkit-keyframes bounceOutDown {
        0% {
            -webkit-transform: translateY(0)
        }
        20% {
            opacity: 1;
            -webkit-transform: translateY(-20px)
        }
        100% {
            opacity: 0;
            -webkit-transform: translateY(2000px)
        }
    }

    @keyframes bounceOutDown {
        0% {
            transform: translateY(0)
        }
        20% {
            opacity: 1;
            transform: translateY(-20px)
        }
        100% {
            opacity: 0;
            transform: translateY(2000px)
        }
    }

    @-webkit-keyframes bounceOutLeft {
        0% {
            -webkit-transform: translateX(0)
        }
        20% {
            opacity: 1;
            -webkit-transform: translateX(20px)
        }
        100% {
            opacity: 0;
            -webkit-transform: translateX(-2000px)
        }
    }

    @keyframes bounceOutLeft {
        0% {
            transform: translateX(0)
        }
        20% {
            opacity: 1;
            transform: translateX(20px)
        }
        100% {
            opacity: 0;
            transform: translateX(-2000px)
        }
    }

    @-webkit-keyframes bounceOutRight {
        0% {
            -webkit-transform: translateX(0)
        }
        20% {
            opacity: 1;
            -webkit-transform: translateX(-20px)
        }
        100% {
            opacity: 0;
            -webkit-transform: translateX(2000px)
        }
    }

    @keyframes bounceOutRight {
        0% {
            transform: translateX(0)
        }
        20% {
            opacity: 1;
            transform: translateX(-20px)
        }
        100% {
            opacity: 0;
            transform: translateX(2000px)
        }
    }

    @-webkit-keyframes fadeOut {
        0% {
            opacity: 1
        }
        100% {
            opacity: 0
        }
    }

    @keyframes fadeOut {
        0% {
            opacity: 1
        }
        100% {
            opacity: 0
        }
    }

    @-webkit-keyframes fadeOutUp {
        0% {
            opacity: 1;
            -webkit-transform: translateY(0)
        }
        100% {
            opacity: 0;
            -webkit-transform: translateY(-2000px)
        }
    }

    @keyframes fadeOutUp {
        0% {
            opacity: 1;
            transform: translateY(0)
        }
        100% {
            opacity: 0;
            transform: translateY(-2000px)
        }
    }

    @-webkit-keyframes fadeOutDown {
        0% {
            opacity: 1;
            -webkit-transform: translateY(0)
        }
        100% {
            opacity: 0;
            -webkit-transform: translateY(2000px)
        }
    }

    @keyframes fadeOutDown {
        0% {
            opacity: 1;
            transform: translateY(0)
        }
        100% {
            opacity: 0;
            transform: translateY(2000px)
        }
    }

    @-webkit-keyframes fadeOutLeft {
        0% {
            opacity: 1;
            -webkit-transform: translateX(0)
        }
        100% {
            opacity: 0;
            -webkit-transform: translateX(-2000px)
        }
    }

    @keyframes fadeOutLeft {
        0% {
            opacity: 1;
            transform: translateX(0)
        }
        100% {
            opacity: 0;
            transform: translateX(-2000px)
        }
    }

    @-webkit-keyframes fadeOutRight {
        0% {
            opacity: 1;
            -webkit-transform: translateX(0)
        }
        100% {
            opacity: 0;
            -webkit-transform: translateX(2000px)
        }
    }

    @keyframes fadeOutRight {
        0% {
            opacity: 1;
            transform: translateX(0)
        }
        100% {
            opacity: 0;
            transform: translateX(2000px)
        }
    }

    @-webkit-keyframes flipOutX {
        0% {
            -webkit-transform: perspective(400px) rotateX(0);
            opacity: 1
        }
        100% {
            -webkit-transform: perspective(400px) rotateX(90deg);
            opacity: 0
        }
    }

    @keyframes flipOutX {
        0% {
            transform: perspective(400px) rotateX(0);
            opacity: 1
        }
        100% {
            transform: perspective(400px) rotateX(90deg);
            opacity: 0
        }
    }

    @-webkit-keyframes flipOutY {
        0% {
            -webkit-transform: perspective(400px) rotateY(0);
            opacity: 1
        }
        100% {
            -webkit-transform: perspective(400px) rotateY(90deg);
            opacity: 0
        }
    }

    @keyframes flipOutY {
        0% {
            transform: perspective(400px) rotateY(0);
            opacity: 1
        }
        100% {
            transform: perspective(400px) rotateY(90deg);
            opacity: 0
        }
    }

    @-webkit-keyframes lightSpeedOutRight {
        0% {
            -webkit-transform: translateX(0) skewX(0);
            opacity: 1
        }
        100% {
            -webkit-transform: translateX(100%) skewX(-30deg);
            opacity: 0
        }
    }

    @keyframes lightSpeedOutRight {
        0% {
            transform: translateX(0) skewX(0);
            opacity: 1
        }
        100% {
            transform: translateX(100%) skewX(-30deg);
            opacity: 0
        }
    }

    @-webkit-keyframes lightSpeedOutLeft {
        0% {
            -webkit-transform: translateX(0) skewX(0);
            opacity: 1
        }
        100% {
            -webkit-transform: translateX(-100%) skewX(30deg);
            opacity: 0
        }
    }

    @keyframes lightSpeedOutLeft {
        0% {
            transform: translateX(0) skewX(0);
            opacity: 1
        }
        100% {
            transform: translateX(-100%) skewX(30deg);
            opacity: 0
        }
    }

    @-webkit-keyframes rotateOut {
        0% {
            -webkit-transform-origin: center center;
            -webkit-transform: rotate(0);
            opacity: 1
        }
        100% {
            -webkit-transform-origin: center center;
            -webkit-transform: rotate(200deg);
            opacity: 0
        }
    }

    @keyframes rotateOut {
        0% {
            transform-origin: center center;
            transform: rotate(0);
            opacity: 1
        }
        100% {
            transform-origin: center center;
            transform: rotate(200deg);
            opacity: 0
        }
    }

    @-webkit-keyframes rotateOutUpLeft {
        0% {
            -webkit-transform-origin: left bottom;
            -webkit-transform: rotate(0);
            opacity: 1
        }
        100% {
            -webkit-transform-origin: left bottom;
            -webkit-transform: rotate(-90deg);
            opacity: 0
        }
    }

    @keyframes rotateOutUpLeft {
        0% {
            transform-origin: left bottom;
            transform: rotate(0);
            opacity: 1
        }
        100% {
            -transform-origin: left bottom;
            -transform: rotate(-90deg);
            opacity: 0
        }
    }

    @-webkit-keyframes rotateOutDownLeft {
        0% {
            -webkit-transform-origin: left bottom;
            -webkit-transform: rotate(0);
            opacity: 1
        }
        100% {
            -webkit-transform-origin: left bottom;
            -webkit-transform: rotate(90deg);
            opacity: 0
        }
    }

    @keyframes rotateOutDownLeft {
        0% {
            transform-origin: left bottom;
            transform: rotate(0);
            opacity: 1
        }
        100% {
            transform-origin: left bottom;
            transform: rotate(90deg);
            opacity: 0
        }
    }

    @-webkit-keyframes rotateOutUpRight {
        0% {
            -webkit-transform-origin: right bottom;
            -webkit-transform: rotate(0);
            opacity: 1
        }
        100% {
            -webkit-transform-origin: right bottom;
            -webkit-transform: rotate(90deg);
            opacity: 0
        }
    }

    @keyframes rotateOutUpRight {
        0% {
            transform-origin: right bottom;
            transform: rotate(0);
            opacity: 1
        }
        100% {
            transform-origin: right bottom;
            transform: rotate(90deg);
            opacity: 0
        }
    }

    @-webkit-keyframes rollOut {
        0% {
            opacity: 1;
            -webkit-transform: translateX(0) rotate(0)
        }
        100% {
            opacity: 0;
            -webkit-transform: translateX(100%) rotate(120deg)
        }
    }

    @keyframes rollOut {
        0% {
            opacity: 1;
            transform: translateX(0) rotate(0)
        }
        100% {
            opacity: 0;
            transform: translateX(100%) rotate(120deg)
        }
    }

    @-webkit-keyframes fadeInUpShort {
        0% {
            opacity: 0;
            -webkit-transform: translateY(20px)
        }
        100% {
            opacity: 1;
            -webkit-transform: translateY(0)
        }
    }

    @keyframes fadeInUpShort {
        0% {
            opacity: 0;
            transform: translateY(20px)
        }
        100% {
            opacity: 1;
            transform: translateY(0)
        }
    }

    @-webkit-keyframes fadeInDownShort {
        0% {
            opacity: 0;
            -webkit-transform: translateY(-20px)
        }
        100% {
            opacity: 1;
            -webkit-transform: translateY(0)
        }
    }

    @keyframes fadeInDownShort {
        0% {
            opacity: 0;
            transform: translateY(-20px)
        }
        100% {
            opacity: 1;
            transform: translateY(0)
        }
    }

    @-webkit-keyframes fadeInRightShort {
        0% {
            opacity: 0;
            -webkit-transform: translateX(20px)
        }
        100% {
            opacity: 1;
            -webkit-transform: translateX(0)
        }
    }

    @keyframes fadeInRightShort {
        0% {
            opacity: 0;
            transform: translateX(20px)
        }
        100% {
            opacity: 1;
            transform: translateX(0)
        }
    }

    @-webkit-keyframes fadeInLeftShort {
        0% {
            opacity: 0;
            -webkit-transform: translateX(-20px)
        }
        100% {
            opacity: 1;
            -webkit-transform: translateX(0)
        }
    }

    @keyframes fadeInLeftShort {
        0% {
            opacity: 0;
            transform: translateX(-20px)
        }
        100% {
            opacity: 1;
            transform: translateX(0)
        }
    }

    /*******************************
  * MODAL AS LEFT/RIGHT SIDEBAR
  * Add "left" or "right" in modal parent div, after class="modal".
  * Get free snippets on bootpen.com
  *******************************/
    .padd-0{
      padding: 0;
    }
    .row{
      margin-left: 0;
      margin-right: 0;
    }
    .padd-1{
      padding: 2px;
    }
    .modal.left .modal-dialog,
    .modal.right .modal-dialog {
      position: fixed;
      margin: auto;
      width: 80%;
      height: 100%;
      -webkit-transform: translate3d(0%, 0, 0);
      -ms-transform: translate3d(0%, 0, 0);
      -o-transform: translate3d(0%, 0, 0);
      transform: translate3d(0%, 0, 0);
    }

    .modal.left .modal-content,
    .modal.right .modal-content {
      height: 100%;
      overflow-y: auto;
    }

    .modal.left .modal-body, .modal.right .modal-body {
      padding: 0;
      background: #b1adad;
    }
    .container-fluid {
      padding-right: 0;
      padding-left: 0;
      margin-right: auto;
      margin-left: auto;
    }
    /*Left*/
    .modal.left.fade .modal-dialog{
      left: -320px;
      -webkit-transition: opacity 0.3s linear, left 0.3s ease-out;
      -moz-transition: opacity 0.3s linear, left 0.3s ease-out;
      -o-transition: opacity 0.3s linear, left 0.3s ease-out;
      transition: opacity 0.3s linear, left 0.3s ease-out;
    }

    .modal.left.fade.in .modal-dialog{
      left: 0;
    }

    /*Right*/
    .modal.right.fade .modal-dialog {
      right: -80%;
      -webkit-transition: opacity 0.3s linear, right 0.3s ease-out;
      -moz-transition: opacity 0.3s linear, right 0.3s ease-out;
      -o-transition: opacity 0.3s linear, right 0.3s ease-out;
      transition: opacity 0.3s linear, right 0.3s ease-out;
    }

    .modal.right.fade.in .modal-dialog {
      right: 0;
    }
    button.close {
      -webkit-appearance: none;
      padding: 21px;
      cursor: pointer;
      opacity: 1;
      color: #fff;
      background: #0ab718;
      position: fixed;
      border: 0;
      top: 0;
      left: 219px;
      z-index: 99;
    }
    .close:focus, .close:hover {
      color: #000;
      text-decoration: none;
      cursor: pointer;
      filter: alpha(opacity=50);
      opacity: 0.8;
    }
    /* ----- MODAL STYLE ----- */
    .modal-content {
      border-radius: 0;
      border: none;
    }

    .modal-header {
      border-bottom-color: #EEEEEE;
      background-color: #FAFAFA;
    }

    .demo-footer > a {
      text-decoration: none;
      font-weight: bold;
      font-size: 16px;
      color: #fff;
    }


    .tabs-left {
      border-bottom: none;
      padding-top: 2px;
      /* border-right: 1px solid #ddd; */
      padding-left: 10px;
    }
    .tabs-left>li {
      float: none!important;
      margin-bottom: 2px!important;
      margin-right: -1px;
      margin-top: 10px;
    }
    .nav-tabs>li.active>a {
      color: #fbfbfb;
      cursor: default;
      background-color: #424141;
      border: 1px solid #ddd;
      /* border-bottom-color: transparent; */
    }
    .tabs-left>li.active>a, .tabs-left>li.active>a:hover, .tabs-left>li.active>a:focus {
      color: #f9f7f7;
      cursor: default;
      background-color: #888484;
      border: 1px solid #ddd;
      border-bottom-color: transparent;
      border-bottom-color: #ddd;
      border-right-color: transparent;
    }
    .tabs-left>li.active>a::after {
      content: '';
      position: absolute;
      right: -10px;
      top: 31%;
      z-index: 99;
      width: 11px;
      height: 11px;
      clear: both;
      border-top: 6px solid transparent;
      border-bottom: 8px solid transparent;
      border-left: 11px solid #888484;
    }
    .tab-content {
      background: #ececec;
      color: #000;
      padding: 10px;
      margin-top: 2px;
    }
    .tabs-left>li>a {
      border-radius: 4px 0 0 4px;
      margin-right: 0;
      display:block;
    }
    .header {
      text-align: right;
      border-bottom: 1px solid #b1adad;
    }


    .selectall {
      background: #ffffff;
      display: inline-block;
      padding: 6px;
      margin-bottom: 7px;
      border-radius: 5px;
      color: #fff;
      width: 24%;
      text-align: center;
    }

    .header p{
      display: inline-block;
      margin-bottom: 0;
    }

    .btn_check
    input {
      display: none;
    }
    .btn_check i {
      width: 14px;
      text-align: left;
    }
    .btn_check input:checked + label {
      color: #ffffff;
      background-color: #47a447;
      border-color: #398439;
      -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);

    }
    .btn_check label.btn.btn-default {
      width: 100%;
      margin-bottom: 10px;
      font-size: 15px;
      letter-spacing: 1px;
    }
    .series-btn {
      margin-top: 20px;
    }
    .selectall  input[type=checkbox] {
      display: none;
    }
    .selectall label {
      background: #fff;
      font-weight: 400;
      padding: 3px;
      /* margin-bottom: 7px; */
      font-size: 16px;
      margin-bottom: 0;
      color: #000;
    }
    .selectall input[type=checkbox]+label:after {
      content: "";
      background: #fff;
      border: 1px solid #a7a7a7;
      display: inline-block;
      width: 16px;
      height: 16px;
      position: inherit;
      margin-bottom: -2px;
      margin-left: 3px;
    }
    .selectall input[type=checkbox]:checked+label:after {
      content: "";
      background: #00a600;
      border: none;
    }
    .second-row {
      margin: 20px 0px 10px;
      border-top: 1px solid #b1adad;
      padding-top: 10px;
    }
    .amnt .input-group {
      width: 100%;

      margin-bottom: 5px;
    }
    .amnt .input-group-addon:first-child {
      border-right: 0;
      font-size: 14px;
      padding-right: 10px;
      padding-left: 10px;
      background: #47a447;
      color: #fff;
    }
    .amnt .input-group .form-control:last-child {
      border-top-left-radius: 0;
      border-bottom-left-radius: 0;
      font-size: 14px;
      padding: 0;
    }
    .size-input-span {
      margin-left: 7px;
      margin-right: 2px;
      width: 95%;
      display: inline-block;
      position: relative;
    }
    .size-input-span>span {
      position: absolute;
      left: 0;
      padding-right: 5px;
      border-right: 1px solid #ccc;
      height: 33px;
      padding-top: 7px;
      padding-left: 5px;
    }
    .size-input-span input {
      width: 100%;
      padding: 2px 0px 2px 59px;
      text-align: center;
      height: 34px;
      border-radius: 3px;
      border: 1px solid #ccc;
    }
    .bdr-top {
      border-top: 1px solid #b1adad;
      /* margin-bottom: 2px; */
    }
    .mt-10 {
      margin-top: 8px;
    }
    .sve {
      text-align: center;
      margin-top: 20px;
    }
    .sve a:hover {
      background: #39900d;
      color: #fff;
    }
    .sve a:active {
      background: #39900d;
      color: #fff;
    }
    .tabs-left>li>a {
      border-radius: 5px;
      margin-right: 0;
      border: 1px solid #ccc;
      display: block;
    }
    .panel-default>.panel-heading {
      color: #333;
      background-color: #ffffff;
      border-color: #ddd;
      padding: 17px;
    }
    .panel-default>.panel-heading a:after {
      content: "\f107";
      position: relative;
      top: 1px;
      display: inline-block;
      font-family: 'FontAwesome';
      font-style: normal;
      font-weight: 400;
      line-height: 1;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      float: right;
      transition: transform .25s linear;
      -webkit-transition: -webkit-transform .25s linear;
    }
    .panel-group .panel+.panel {
      margin-top: 5px;
    }
    .panel {
      border: 1px solid #eee;
      /* border-left: 4px solid #ff7d52; */
      border-radius: 0 4px 4px 0!important;
      -webkit-box-shadow: 0 2px 3px hsla(0,0%,65.5%,.41);
      box-shadow: 0 2px 3px hsla(0,0%,65.5%,.41);
      padding: 10px;
    }
    .panel-heading {
      padding: 0px 15px;
      border-bottom: 1px solid transparent;
      border-top-left-radius: 3px;
      border-top-right-radius: 3px;
    }
    .cat-one-title, .cat-two-title {
      padding: 8px 0 0;
      position: relative;
    }

    .panel-heading a {
      font-size: 17px;
      color: rgba(44,44,44,.72);
      font-weight: 600;
      text-decoration: none;
      display: block;
      text-align: center;
      margin-bottom: -10px;
    }
    .cat-one-sub-block {
      border-top: 1px solid #ccc;
      padding-top: 10px;
    }
    .one-cat-sub-block-one {
      position: relative;
      background: #ccc;
      padding: 8px;
      margin: 5px;
    }
    .sidebar input[type=checkbox] {
      display: none;
    }

    .sidebar input[type=checkbox]+label:after {
      content: "";
      background: #fff;
      border: 1px solid #a7a7a7;
      display: inline-block;
      width: 18px;
      height: 18px;
      position: absolute;
      right: 5px;
      top: 8px;
    }
    .sidebar input[type=checkbox]:checked+label:after {
      content: "";
      background: #00a600;
      border: none;
    }

    .box-1 {
      padding: 2px;
      padding-top: 0;
      background: #f3f0f0;
      margin-bottom: 2px;
    }
    .avl-head h3 {
      margin: 4px;
      font-size: 16px;
      padding: 4px;
    }
    .avl-sel ul{
      padding: 0;
    }
    .avl-sel ul li {
      list-style: none;
      display: inline-block;
      margin-left: 4px;
      margin-right: 4px;
      padding: 5px;
      font-size: 13px;
      /* padding: 0px; */
      background: #fff;
      border-radius: 5px;
    }
    .avl-sel ul li p {
      margin: 0;
      padding-left: 2px;
      padding-right: 0px;
    }
    .panel-default>.panel-heading+.panel-collapse>.panel-body {
      border-top-color: #ddd;
      padding: 0;
    }
    .one-cat-sub-block-one input[type=checkbox]+label:after {
      content: "";
      background: #fff;
      border: 1px solid #a7a7a7;
      display: inline-block;
      width: 18px;
      height: 18px;
      position: absolute;
      right: 5px;
      top: 9px;
    }
    .bg-white{
      background: #fff;
    }
    .padd-left0{
      padding-right: 0;
    }
    .mt-0{
      margin-top: 0!important;
    }
    .modal-header h4{
      margin: 0;
    }
    .sve a {
      font-size: 18px;
      width: 22%;
    }
</style>
