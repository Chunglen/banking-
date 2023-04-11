<!DOCTYPE html>
<html>
<head>
    <title>Banking App Interface</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .header {
            background-color: #3F51B5;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            margin: 20px;
            padding: 20px;
            background-color: #F5F5F5;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.3);
        }

        .row {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: center;
            margin: 10px;
            padding: 10px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }

        .column {
            display: flex;
            flex-direction: column;
            margin: 10px;
            padding: 10px;
        }

        .button {
            background-color: #3F51B5;
            color: #fff;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.2s;
        }

        .button:hover {
            background-color: #303F9F;
            color: #fff;
        }

        .input {
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            margin-bottom: 10px;
            width: 100%;
            box-sizing: border-box;
            font-size: 16px;
            color: #333;
        }

    </style>
</head>
<body>
    <div class="header">
        <h1>Banking App Interface</h1>
    </div>
    <div class="container">
        <div class="row">
            <div class="column">
                <h2>Account Details</h2>
                <p><strong>Account Number:</strong> 123456789</p>
                <p><strong>Balance:</strong> $1000</p>
                <p><strong>Last Transaction:</strong> $50 at Grocery Store</p>
            </div>
            <div class="column">
                <h2>Account Options</h2>
                <button class="button">View Transactions</button>
                <button class="button">Transfer Money</button>
                <button class="button">Pay Bill</button>
            </div>
        </div>
        <div class="row">
            <div class="column">
                <h2>Transfer Money</h2>
                <input type="text" class="input" placeholder="Recipient's Account Number">
                <input type="text" class="input" placeholder="Amount">
                <button class="button">Transfer</button>
            </div>
            <div class="column">
                <h2>Pay Bill</h2>
                <input type="text" class="input" placeholder="Payee Name">
                <input type="text" class="input" placeholder="Amount">
                <button
