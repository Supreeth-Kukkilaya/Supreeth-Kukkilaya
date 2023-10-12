
<!DOCTYPE html>
<html>
    <head>
        <title> GSMS </title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
        <meta name="apple-mobile-web-app-capable" content="yes"/>
        <meta name="csrf-token" content="kmapods5wQ5L1hn7rcR9OPst7EsN0gC7SrHh3m9K"/>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/material-design-iconic-font/2.2.0/css/material-design-iconic-font.min.css">
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:400,300,600,700">
        <link media="all" type="text/css" rel="stylesheet" href="css/bootstrap.min.css">
        <link media="all" type="text/css" rel="stylesheet" href="css/style.css?v=1.0">
        <link media="all" type="text/css" rel="stylesheet" href="css/sidebar-menu.css?v=1.0">
        <link media="all" type="text/css" rel="stylesheet" href="css/custom.css?v=1.3.3">
    </head>
    <body class="tooltips">
        <div class="container">

            <div class="header content rows-content-header">
                <button class="button-menu-mobile show-sidebar">
                    <i class="fa fa-bars"></i>
                </button>
                <div class="navbar navbar-default" role="navigation">
                    <div class="container">

                        <div class="navbar-collapse collapse">
                            <ul class="nav navbar-nav visible-lg visible-md limit-chars">
                                <ul class="breadcrumb">
                                    <a href="index.html">
                                        <i class="zmdi zmdi-view-dashboard zmdi-hc-fw" title="Orders"></i>
                                    </a>
                                    <a href="manage-product.html">
                                        <i class="zmdi zmdi-assignment zmdi-hc-fw" title="Products"></i>
                                    </a>
                                </ul>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>

            <div class="right content-page">
                <div class="body content rows scroll-y">
                    <form class="form-horizontal" action="">
                        <div class="box-info full" id="taskFormContainer">
                            <h2>Grocery Management System</h2>
                            <div class="panel-body pt-0">
                                <div class="row mb-4">
                                    <div class="col-sm-12">
                                        <a href="order.html" class="btn btn-sm btn-primary pull-right ml-3">
                                            New Order
                                        </a>
                                        <a href="manage-product.html" class="btn btn-sm btn-primary pull-right">
                                            Manage Products
                                        </a>
                                    </div>
                                </div>
                                <table class="table table-bordered">
                                    <thead>
                                        <th>Date</th>
                                        <th>Order Number</th>
                                        <th>Customer Name</th>
                                        <th>Total Cost</th>
                                    </thead>
                                    <tbody>

                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </form>
                    <div class="modal " id="userProfileModal" role="dialog" >
                        <div class="modal-dialog">
                            <div class="modal-content">
                                <div class="modal-body text-center">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="modal fade-scale" id="myModal" role="dialog" data-backdrop="static">
                <div class="modal-dialog modal-lg">
                    <div class="modal-content">
                        <div class="modal-body text-center">
                            <img src="https://demo.test.cloint.com/assets/images/spinner.gif" width="40" style="margin: 60px auto;" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </body>
    
    <script src="js/packages/jquery.min.js"></script>
    <script src="js/custom/common.js"></script>
    <script src="js/custom/dashboard.js"></script>
</html>
