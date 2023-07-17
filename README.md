<html lang="en">

<head>
    <title> FX2 WhatsApp World </title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
</head>

<body onload="readyfn(this)">

    <div style="background-color: #202D30; min-height: 45px;padding-left: 10px; padding-right: 10px;">
        <div style="float: left; width: 50%;">
            <img alt="Braintoy Logo" border="0" class="float: left;"
                src="https://static.wixstatic.com/media/1a4da9_cd056aab6d754dae98dc60083c4317a8~mv2.png"
                style="text-decoration: none; -ms-interpolation-mode: bicubic; height: auto; border: none; width: 100%; max-width: 150px; display: block;"
                title="Braintoy Logo" width="200" />
        </div>
        <div style="float: right; width: 50%; ">
            <span style="color: white; float: right; font-size: 30px;"> Foreign Exchange Prediction Tool </span>
        </div>
    </div>
    <div class="w3-bar" style=" padding: 20px;">
        <div class="w3-half" style="min-height: 880px;padding: 10px;">
            <div class="w3-bar">
                <h3>Input(s) to the model</h3>
            </div>
            <div class="w3-bar" style="border: 1px solid lightblue ; padding: 10px; border-radius: 10px; ">
                <div class="w3-bar" style="min-height: 800px;max-height: 800px; overflow-y: auto;">
                    <div id="id_mlos_prediction">
                        <div class="form-group"><label for="EURUSD_Open">EURUSD_Open:</label> <input type="text" value ="1.1961007118" id="input_feature_1" class="form-control"  name="EURUSD_Open"></div><div class="form-group"><label for="EURUSD_High">EURUSD_High:</label> <input type="text" value ="1.2109030485" id="input_feature_2" class="form-control"  name="EURUSD_High"></div><div class="form-group"><label for="EURUSD_Low">EURUSD_Low:</label> <input type="text" value ="1.1946003437" id="input_feature_3" class="form-control"  name="EURUSD_Low"></div><div class="form-group"><label for="USDJPY_Open">USDJPY_Open:</label> <input type="text" value ="109.1800003052" id="input_feature_4" class="form-control"  name="USDJPY_Open"></div><div class="form-group"><label for="USDJPY_High">USDJPY_High:</label> <input type="text" value ="109.7799987793" id="input_feature_5" class="form-control"  name="USDJPY_High"></div><div class="form-group"><label for="USDJPY_Low">USDJPY_Low:</label> <input type="text" value ="108.4800033569" id="input_feature_6" class="form-control"  name="USDJPY_Low"></div><div class="form-group"><label for="GBPUSD_Open">GBPUSD_Open:</label> <input type="text" value ="1.7190104723" id="input_feature_7" class="form-control"  name="GBPUSD_Open"></div><div class="form-group"><label for="GBPUSD_High">GBPUSD_High:</label> <input type="text" value ="1.7321116924" id="input_feature_8" class="form-control"  name="GBPUSD_High"></div><div class="form-group"><label for="GBPUSD_Low">GBPUSD_Low:</label> <input type="text" value ="1.7172982693" id="input_feature_9" class="form-control"  name="GBPUSD_Low"></div><div class="form-group"><label for="AUDUSD_Open">AUDUSD_Open:</label> <input type="text" value ="None" id="input_feature_10" class="form-control"  name="AUDUSD_Open"></div><div class="form-group"><label for="AUDUSD_High">AUDUSD_High:</label> <input type="text" value ="None" id="input_feature_11" class="form-control"  name="AUDUSD_High"></div><div class="form-group"><label for="AUDUSD_Low">AUDUSD_Low:</label> <input type="text" value ="None" id="input_feature_12" class="form-control"  name="AUDUSD_Low"></div><div class="form-group"><label for="EURGBP_Open">EURGBP_Open:</label> <input type="text" value ="0.6955999732" id="input_feature_13" class="form-control"  name="EURGBP_Open"></div><div class="form-group"><label for="EURGBP_High">EURGBP_High:</label> <input type="text" value ="0.6991000175" id="input_feature_14" class="form-control"  name="EURGBP_High"></div><div class="form-group"><label for="EURGBP_Low">EURGBP_Low:</label> <input type="text" value ="0.6941000223" id="input_feature_15" class="form-control"  name="EURGBP_Low"></div><div class="form-group"><label for="EURCAD_Open">EURCAD_Open:</label> <input type="text" value ="1.5598000288" id="input_feature_16" class="form-control"  name="EURCAD_Open"></div><div class="form-group"><label for="EURCAD_High">EURCAD_High:</label> <input type="text" value ="1.5707999468" id="input_feature_17" class="form-control"  name="EURCAD_High"></div><div class="form-group"><label for="EURCAD_Low">EURCAD_Low:</label> <input type="text" value ="1.5590000153" id="input_feature_18" class="form-control"  name="EURCAD_Low"></div><div class="form-group"><label for="USDCNY_Open">USDCNY_Open:</label> <input type="text" value ="8.2572002411" id="input_feature_19" class="form-control"  name="USDCNY_Open"></div><div class="form-group"><label for="USDCNY_High">USDCNY_High:</label> <input type="text" value ="8.2672014236" id="input_feature_20" class="form-control"  name="USDCNY_High"></div><div class="form-group"><label for="USDCNY_Low">USDCNY_Low:</label> <input type="text" value ="8.2572002411" id="input_feature_21" class="form-control"  name="USDCNY_Low"></div><div class="form-group"><label for="USDINR_Open">USDINR_Open:</label> <input type="text" value ="45.7089996338" id="input_feature_22" class="form-control"  name="USDINR_Open"></div><div class="form-group"><label for="USDINR_High">USDINR_High:</label> <input type="text" value ="45.71900177" id="input_feature_23" class="form-control"  name="USDINR_High"></div><div class="form-group"><label for="USDINR_Low">USDINR_Low:</label> <input type="text" value ="45.5600013733" id="input_feature_24" class="form-control"  name="USDINR_Low"></div>

                    </div>
                </div>
            </div>
        </div>
        <div class="w3-half" style="min-height: 880px;padding: 10px;">
            <div id="id_hide_if_api_key_embedded" class="w3-bar w3-show">
                <div class="w3-bar">
                    <h3>API Key</h3>
                </div>
                <div class="w3-bar" style="border: 1px solid lightblue ; padding: 10px; border-radius: 10px; ">
                    <div class="w3-bar" style="min-height: 100px;max-height: 800px; overflow-y: auto;">
                        <div id="id_mlos_prediction">
                            <div class="form-group">
                                <label for="apikey">apikey:</label>
                                <input type="password" id="apikey" class="form-control" name="apikey">
                                </div>
                            <div class="form-group">
                                <label for="accesstoken">accesstoken:</label>
                                <input type="password" id="accesstoken" class="form-control" name="accesstoken">
                            </div>

<script>
    // Get the input elements
    var apikeyInput = document.getElementById('apikey');
    var accessTokenInput = document.getElementById('accesstoken');

    // Set the pre-filled values
    apikeyInput.value = '94815e7ca9b4456dbc755f310ab925178e91a8c485e84f7db72f989be85008fb';
    accessTokenInput.value = 'eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyIxIjoiMV9rZHVib3ZldHNreWlnbWFpbGNvbV9iNDU1OWI3Y2QwMDI0MTQwOTI2YTIxMjI4NzU1ZjY2YSJ9.3LcDZxKUsUo5YMOQD3P_2RPdvQZ2RSIin7M1ZOndmLU';
</script>

                        </div>
                    </div>
                </div>
            </div>
            <div class="w3-bar">
                <h3>Model Output</h3>
            </div>
            <div class="w3-bar" style="border: 1px solid lightblue ; padding: 10px; border-radius: 10px;">
                <div id="id_warning_val" class="w3-bar w3-hide">
                    <span id="id_msg_container" style="color: orange;font-size: 14px; "> Invalid APIkey or Access Token,
                        Please change APIkey.
                    </span>
                </div>
                <div class="w3-bar" style="padding-left: 350px;padding-right: 150px;">
                    <button onclick="btn_click_predict(this)" class="btn btn-default w3-left">Predict</button>
                </div>
                <div class="w3-bar" style="padding-top: 30px;padding-left: 100px;padding-right: 100px;">
                    <div class="w3-half" style="padding: 15px;">
                        <span style="font-size: 18px;">Response From Model</span>
                        <div class="w3-bar " style="border: 1px solid lightblue; border-radius: 10px; padding: 20px;">
                            <span id="id_response_1" style="font-size: 18px;">[]</span>
                        </div>
                    </div>
                    <div class="w3-half" style="padding: 15px;">
                        <span style="font-size: 18px;"> Transformed Response</span>
                        <div class="w3-bar " style="border: 1px solid lightblue; border-radius: 10px;padding: 20px;">
                            <span id="id_response_2" style="font-size: 18px;">[]</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="w3-bar">
                <div class="w3-half" style="padding: 3px;">
                    <div class="w3-bar">
                        <h3>Model Response Log</h3>
                    </div>
                    <div class="w3-bar"
                        style="border: 1px solid lightblue ; padding: 10px; border-radius: 10px; margin-top: 10px; max-height: 300px; min-height: 300px; overflow-y: auto;">
                        <div id="id_mlos_predict_log">

                        </div>
                    </div>
                </div>
                <div class="w3-half" style="padding: 3px;">
                    <div class="w3-bar">
                        <h3>Why ?</h3>
                    </div>
                    <div class="w3-bar"
                        style="border: 1px solid lightblue ; padding: 10px; border-radius: 10px; margin-top: 10px; max-height: 300px; min-height: 300px; overflow-y: auto;">
                        <div class="w3-bar">
                            <span > Probabilistic Prediction  </span>
                        </div>
                        <div class="w3-bar">
                            <div class="w3-bar" id="id_model_explain_prob">

                            </div>
                        </div>
                        <div class="w3-bar">
                            <div class="w3-bar">
                                <div class="w3-bar" style="border-bottom: 1px solid green;">
                                    <span>Influential Inputs</span>
                                </div>
                                <div class="w3-bar" id="id_model_explain_response_good">

                                </div>
                            </div>
                            <div class="w3-bar">
                                <div class="w3-bar " style="border-bottom: 1px solid red;">
                                    <span>Noninfluential Inputs</span>
                                </div>
                                <div class="w3-bar" id="id_model_explain_response_bad">

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>


        </div>
    </div>


    <div style="background-color: #202D30; min-height: 30px;padding-left: 10px; padding-right: 10px;top: 100%;">
        &nbsp;
    </div>
</body>
<script>
    var feature_list = {"columns": ["EURUSD_Open", "EURUSD_High", "EURUSD_Low", "USDJPY_Open", "USDJPY_High", "USDJPY_Low", "GBPUSD_Open", "GBPUSD_High", "GBPUSD_Low", "AUDUSD_Open", "AUDUSD_High", "AUDUSD_Low", "EURGBP_Open", "EURGBP_High", "EURGBP_Low", "EURCAD_Open", "EURCAD_High", "EURCAD_Low", "USDCNY_Open", "USDCNY_High", "USDCNY_Low", "USDINR_Open", "USDINR_High", "USDINR_Low"], "index": [0, 1, 2], "data": [[1.2033983469, 1.2040069103, 1.1944006681, 109.8300018311, 109.9899978638, 109.0500030518, 1.7238109112, 1.7272051573, 1.7183902264, null, null, null, 0.6973999739, 0.6977000237, 0.6937000155, 1.5615999699, 1.5666999817, 1.5542000532, 8.2670001984, 8.2672014236, 8.2670001984, 45.7089996338, 45.7280006409, 45.6150016785], [1.1961007118, 1.2109030485, 1.1946003437, 109.1800003052, 109.7799987793, 108.4800033569, 1.7190104723, 1.7321116924, 1.7172982693, null, null, null, 0.6955999732, 0.6991000175, 0.6941000223, 1.5598000288, 1.5707999468, 1.5590000153, 8.2572002411, 8.2672014236, 8.2572002411, 45.7089996338, 45.71900177, 45.5600013733], [1.208999753, 1.213003397, 1.2077003717, 108.7300033569, 108.7900009155, 108.0400009155, 1.7304929495, 1.7318116426, 1.7252088785, null, null, null, 0.6988000274, 0.7014999986, 0.6977000237, 1.5664999485, 1.5762000084, 1.564800024, 8.2672014236, 8.2672014236, 8.2671003342, 45.6319999695, 45.65599823, 45.4749984741]]}
    var data_domain = "table"
    var apikey = "_apikey_"
    var accesstoken = "_accesstoken_"
    if (apikey == "_apikey_" && accesstoken == "_accesstoken_") {
        itm = document.getElementById("id_hide_if_api_key_embedded")
        itm.className = itm.className.replace("w3-hide", "w3-show")
    }
    else {
        itm = document.getElementById("id_hide_if_api_key_embedded")
        itm.className = itm.className.replace("w3-show", "w3-hide")
    }
    document.getElementById("apikey").value = apikey
    document.getElementById("accesstoken").value = accesstoken
    var req_count = 1
    function readyfn() {
    }
    function show() {
        itm = document.getElementById("id_warning_val")
        itm.className = itm.className.replace("w3-hide", "w3-show")
    }
    function hide() {
        itm = document.getElementById("id_warning_val")
        itm.className = itm.className.replace("w3-show", "w3-hide")
    }
    function btn_click_predict(e) {
        apikey = document.getElementById("apikey").value
        accesstoken = document.getElementById("accesstoken").value
        if (apikey == "_apikey_") {
            show()
            itm = document.getElementById("id_mlos_predict_log")
            spn = document.createElement("div")
            spn.setAttribute("class", "w3-bar")
            spn.innerHTML = "[" + req_count + "]" + " - Unauthorized "
            itm.insertBefore(spn, itm.childNodes[0]);
            req_count = req_count + 1
            return
        }
        else {
            hide()
        }

        var num_features = feature_list["columns"].length
        var data = {
            "data": []
        };
        var feature_important_list = []
        inc = 1
dtx = []
feature_list["columns"].forEach(element => {
tmp = {
"feature": element,
"id": "input_feature_" + inc,
"weight": 0,
"target": 0
}
feature_important_list.push(tmp)
itmv = document.getElementById("input_feature_" + inc).value
dtx.push(itmv)
inc = inc + 1
});
data["data"].push(dtx)
        var xhr = new XMLHttpRequest();
        xhr.withCredentials = true;
        xhr.addEventListener("readystatechange", function () {
            if (this.readyState === 4) {
                resp = []
                try {
                    resp = JSON.parse(this.responseText)

                } catch (error) {
                    itm = document.getElementById("id_mlos_predict_log")
                    spn = document.createElement("div")
                    spn.setAttribute("class", "w3-bar")
                    spn.innerHTML = "[" + req_count + "]" + " - Unauthorized "
                    itm.insertBefore(spn, itm.childNodes[0]);
                }
                if (resp.success == true) {
                    mresp = resp.results.results
                    console.log(mresp)
                    sample_response = mresp.prediction[0]
                    document.getElementById("id_response_1").innerHTML = mresp.prediction[0]
                    document.getElementById("id_response_2").innerHTML = mresp.prediction_transformed[0]
                    itm = document.getElementById("id_mlos_predict_log")
                    spn = document.createElement("div")
                    spn.setAttribute("class", "w3-bar")
                    spn.innerHTML = "[" + req_count + "]" + "MODEL RESPONSE " + mresp.prediction_transformed[0]
                    itm.insertBefore(spn, itm.childNodes[0]);

                    response_explanation = mresp.explanation

                    itm = document.getElementById("id_model_explain_response_bad")
                    itm.innerHTML = ""
                    itm = document.getElementById("id_model_explain_response_good")
                    itm.innerHTML = ""


                    feature_important_list.forEach(element => {
                        response_explanation.forEach(expln => {
                            if (element.feature == expln.feature) {
                                element.weight = expln.weight
                                element.target = expln.target
                                if (expln.normweight > 0.2) {
                                    moditem = document.getElementById(element.id)
                                    moditem.setAttribute("style", "border-bottom:2px solid green;line-height: 50px;")
                                    itm = document.getElementById("id_model_explain_response_good")
                                    spn = document.createElement("span")
                                    spn.setAttribute("class", "w3-block ")
                                    spn.setAttribute("style", "color:green;")
                                    spn.innerHTML = element.feature + " [ " +  expln.weight +   " ] "
                                    itm.insertBefore(spn, itm.childNodes[0]);
                                }
                                else {
                                    moditem = document.getElementById(element.id)
                                    moditem.setAttribute("style", "border-bottom:2px solid red;line-height: 50px;")
                                    itm = document.getElementById("id_model_explain_response_bad")
                                    spn = document.createElement("span")
                                    spn.setAttribute("style", "color:red;")
                                    spn.setAttribute("class", "w3-block")
                                    spn.innerHTML = element.feature + " [ " +  expln.weight +   " ] "
                                    itm.insertBefore(spn, itm.childNodes[0]);
                                }
                            }
                        })
                    })


                    class_label = mresp["class_label"]
                        probability = mresp["probability"][0]
                        if (class_label.length > 0 && probability.length > 0) {
                            inc = 0
                            min = Math.min(probability)
                            max = Math.max(probability)
                            // valx= probability.map(this.normalize(min, max))
                            // // valx= probability-min
                            // console.log(valx)
                            itm = document.getElementById ("id_model_explain_prob")
                            itm.innerHTML = ""
                            class_label.forEach(elm => {

                                spn = document.createElement("span")
                                spn.setAttribute("class", "w3-block win-act-color")
                                spn.setAttribute("style", "color:green;")
                                spn.innerHTML = elm + " [ " + probability[inc] + " ] "
                                itm.appendChild(spn);
                                inc = inc + 1
                            })
                        }
                        else {
                            itm = document.getElementById ("id_model_explain_prob")
                            itm.innerHTML = "No class probability available."
                        }



                }
                else {
                    itm = document.getElementById("id_mlos_predict_log")
                    spn = document.createElement("div")
                    spn.setAttribute("class", "w3-bar")
                    spn.innerHTML = "[" + req_count + "]" + " - ERROR IN MODEL RESPONSE "
                    itm.insertBefore(spn, itm.childNodes[0]);
                }
                req_count = req_count + 1

            }


        });
        xhr.open("POST", "https://www.sait.mlos.io/api/v1/mlasaservice");
        xhr.setRequestHeader("content-type", "application/json");
        xhr.setRequestHeader("authorization", accesstoken);
        xhr.setRequestHeader("apikey", apikey);
        xhr.setRequestHeader("api", "predict");
        xhr.setRequestHeader("cache-control", "no-cache");
        xhr.setRequestHeader("Access-Control-Allow-Origin", "http://127.0.0.1:8080");
        // xhr.setRequestHeader("Access-Control-Content-Type", "*");
        // xhr.setRequestHeader("Access-Control-Allow-Credentials", true);


        xhr.setRequestHeader("app-token", "asdasda-asdasd-c8fd-da41-dd36d45914fc");
        data = JSON.stringify(data)
        xhr.send(data);
    }
    

</script>

</html>
