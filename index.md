<!DOCTYPE html>
<html>
<head>
    <title>Main</title>
    <meta charset="utf-8" />

    <!-- <script src="../Scripts/jquery-1.9.1.min.js"></script> -->
    <script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    <link rel="stylesheet" href="../Css/custom.css">
    
</head>
<body>




    <div class="content">

        <div class="top-widget row">

            <!--current workflow-->

            <div class="current-workflow col-md-4">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">Сurrent workflow</h3>
                    </div>
                    <div class="panel-body">
                        <div class="form-group">
                            <label>Current unique name</label>
                            <div>
                                <div class="btn-group">
                                    <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                        Action <span class="caret"></span>
                                    </button>
                                    <ul class="dropdown-menu">
                                        <li><a href="#">Action</a></li>
                                        <li><a href="#">Another action</a></li>
                                        <li><a href="#">Something else here</a></li>
                                        <li role="separator" class="divider"></li>
                                        <li><a href="#">Separated link</a></li>
                                    </ul>
                                </div>
                            </div>

                        </div>
                        <div class="_align-right">
                            <input class="btn btn-default" type="button" value="Update" name="update" id="update" size="40" />
                            <input class="btn btn-default" type="button" value="Select" name="select" id="select" size="40" />
                        </div>
                    </div>
                </div>
            </div>

            <!--new workflow-->

            <div class="col-md-8">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">New workflow</h3>
                    </div>
                    <div class="panel-body">

                        <div class="row">
                            <div class="col-md-6">
                                <div class="form-group">
                                    <label>New unique name</label>
                                    <input type="text" class="form-control" />
                                </div>
                                <div class="form-group">
                                    <label>Team</label>
                                    <div>
                                        <div class="btn-group">
                                            <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                                Action <span class="caret"></span>
                                            </button>
                                            <ul class="dropdown-menu">
                                                <li><a href="#">Action</a></li>
                                                <li><a href="#">Another action</a></li>
                                                <li><a href="#">Something else here</a></li>
                                                <li role="separator" class="divider"></li>
                                                <li><a href="#">Separated link</a></li>
                                            </ul>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="row">
                                    <div class="col-md-6">
                                        <label>Date from</label>
                                        <div class="form-group">
                                            <div class='input-group date' id='datetimepicker1'>
                                                <input type='text' class="form-control" />
                                                <span class="input-group-addon">
                                                    <span class="glyphicon glyphicon-calendar"></span>
                                                </span>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-md-6">
                                        <div class="form-group">
                                            <label>Date to</label>
                                            <div class='input-group date' id='datetimepicker2'>
                                                <input type='text' class="form-control" />
                                                <span class="input-group-addon">
                                                    <span class="glyphicon glyphicon-calendar"></span>
                                                </span>
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

        <div class="row">
            <div class="col-md-3">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">Daily total transfered interaction</h3>
                    </div>
                    <div class="panel-body">

                      
                            <table class="table table-bordered">
                                <thead>
                                    <tr>
                                        <th></th>
                                        <th>Select</th>
                                        <th>Poor</th>
                                        <th>Avg</th>
                                        <th>Good</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <th><small>ACD voice</small></th>
                                        <td>
                                            <input type="checkbox" />
                                        </td>
                                        <td>Doe</td>
                                        <td>john</td>
                                        <td>john</td>
                                    </tr>
                                    <tr>
                                        <th><small>Non ACD voice</small></th>
                                        <td>
                                            <input type="checkbox" />
                                        </td>
                                        <td>Moe</td>
                                        <td>mar</td>
                                        <td>john</td>
                                    </tr>
                                    <tr>
                                        <th><small>Internal voice</small></th>
                                        <td>
                                            <input type="checkbox" />
                                        </td>
                                        <td>Dooley</td>
                                        <td>july</td>
                                        <td>john</td>
                                    </tr>
                                    <tr>
                                        <th><small>Outband voice</small></th>
                                        <td>
                                            <input type="checkbox" />
                                        </td>
                                        <td>Dooley</td>
                                        <td>july</td>
                                        <td>john</td>
                                    </tr>
                                    <tr>
                                        <th><small>ACD email</small></th>
                                        <td>
                                            <input type="checkbox" />
                                        </td>
                                        <td>Dooley</td>
                                        <td>july</td>
                                        <td>john</td>
                                    </tr>
                                    <tr>
                                        <th><small>ACD fax</small></th>
                                        <td>
                                            <input type="checkbox" />
                                        </td>
                                        <td>Dooley</td>
                                        <td>july</td>
                                        <td>john</td>
                                    </tr>
                                    <tr>
                                        <th><small>ACD dialer</small></th>
                                        <td>
                                            <input type="checkbox" />
                                        </td>
                                        <td>Dooley</td>
                                        <td>july</td>
                                        <td>john</td>
                                    </tr>
                                    <tr>
                                        <th><small>IPA process</small></th>
                                        <td>
                                            <input type="checkbox" />
                                        </td>
                                        <td>Dooley</td>
                                        <td>july</td>
                                        <td>john</td>
                                    </tr>
                                </tbody>
                            </table>


                       

                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">Daily total transfered interaction</h3>
                    </div>
                    <div class="panel-body">


                        <table class="table table-bordered">
                            <thead>
                                <tr>
                                    <th></th>
                                    <th>Select</th>
                                    <th>Poor</th>
                                    <th>Avg</th>
                                    <th>Good</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <th><small>ACD voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Doe</td>
                                    <td>john</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>Non ACD voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Moe</td>
                                    <td>mar</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>Internal voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>Outband voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>ACD email</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>ACD fax</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>ACD dialer</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>IPA process</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                            </tbody>
                        </table>




                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">Daily total transfered interaction</h3>
                    </div>
                    <div class="panel-body">


                        <table class="table table-bordered">
                            <thead>
                                <tr>
                                    <th></th>
                                    <th>Select</th>
                                    <th>Poor</th>
                                    <th>Avg</th>
                                    <th>Good</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <th><small>ACD voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Doe</td>
                                    <td>john</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>Non ACD voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Moe</td>
                                    <td>mar</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>Internal voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>Outband voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>ACD email</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>ACD fax</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>ACD dialer</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>IPA process</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                            </tbody>
                        </table>




                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">Daily total transfered interaction</h3>
                    </div>
                    <div class="panel-body">


                        <table class="table table-bordered">
                            <thead>
                                <tr>
                                    <th class="col-md-3"></th>
                                    <th  class="col-md-3">Select</th>
                                    <th  class="col-md-3">Poor</th>
                                    <th  class="col-md-3">Avg</th>
                                    <th  class="col-md-2">Good</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <th><small>ACD voice</small></th>
                                    <td class="col-md-4">
                                        <input type="checkbox" />
                                    </td>
                                    <td class="col-md-3">Doessss</td>
                                    <td class="col-md-3">john</td>
                                    <td class="col-md-2">john</td>
                                </tr>
                                <tr>
                                    <th><small>Non ACD voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Moe</td>
                                    <td>mar</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>Internal voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooleыыy</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>Outband voice</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>ACD email</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>ACD fax</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>ACD dialer</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                                <tr>
                                    <th><small>IPA process</small></th>
                                    <td>
                                        <input type="checkbox" />
                                    </td>
                                    <td>Dooley</td>
                                    <td>july</td>
                                    <td>john</td>
                                </tr>
                            </tbody>
                        </table>




                    </div>
                </div>
            </div>
            <!--<div class="col-md-3">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">New workflow</h3>
                    </div>
                    <div class="panel-body">
                        <div class="row">
                            <div class="col-md-4">
                                bls
                            </div>

                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">New workflow</h3>
                    </div>
                    <div class="panel-body">
                        <div class="row">
                            <div class="col-md-4">
                                bls
                            </div>

                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">New workflow</h3>
                    </div>
                    <div class="panel-body">
                        <div class="row">
                            <div class="col-md-4">
                                bls
                            </div>

                        </div>
                    </div>
                </div>
            </div>-->
        </div>
    </div>
    <script type="text/javascript">
        $(function () {
            $('#datetimepicker1').datetimepicker();
            $('#datetimepicker2').datetimepicker();
        });
    </script>
</body>

</html>
