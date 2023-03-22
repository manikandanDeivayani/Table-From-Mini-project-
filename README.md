# Table-From-Mini-project-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table{
            width: 600px;
            text-align: left;
            margin-left: auto;
            margin-right: auto;
        }
        table,td,th{
            border: 1px solid rgb(87, 85, 85);
            border-collapse: collapse;
            padding: 8px;
            line-height: 1.3;
            background-color: white;
        }
        th{
            background-color: lightblue;
        }
    </style>
</head>
<body style="background-color: #f2f6ff;">
    <table>
        <tr>
            <th colspan="3">Invoice#12345ABC</th>
            <th>18Jul 2019</th>
        </tr>
        <tr>
            <td colspan="2">
                <span> Pay To:</span><br>
                The Tech Parkb <br>
                123 Willow Street <br>
                Boulevard, LA-567892
            </td>
            <td colspan="2">
                <span>Customer:</span>
                Jhon Lark <br>
                Dummy Apartments <br>
                276 main Street <br>
                Boulevard, LA-567892
            </td>
        </tr>
        <tr>
            <th>Name/Description</th>
            <th>Qty.</th>
            <th>MRP</th>
            <th>Amount</th>
        </tr>
        <tr>
            <td>Biryani</td>
            <td>3</td>
            <td>400</td>
            <td>1200</td>
        </tr>
        <tr>
            <th colspan="3">subtotal:</th>
            <th>1800</td>
        </tr>
        <tr>
            <th colspan="2">Tax</th>
            <td>10%</td>
            <td>180</td>
        </tr>
        <tr>
            <th colspan="3">Grand Total:</th>
            <td>Rs 1620</td>
        </tr>
       
    </table>
</body>
</html>
