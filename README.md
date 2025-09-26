preparing for payroll program

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <title>PAYROLL PROGRAM</title>
    <!-- <style>
        body {
            background: #555;
            font-family: Arial, Helvetica, sans-serif;
        }
        .container {
            background: #fff;
            border: 5px solid #000;
            border-radius: 35px;
            width: 900px;
            margin: 20px auto;
            padding: 30px 40px 40px 40px;
            box-sizing: border-box;
        }
        h1 {
            text-align: center;
            color: #000;
            font-size: 4rem;
            font-weight: bold;
            margin-bottom: 30px;
            letter-spacing: 2px;
        }
        .row {
            display: flex;
            justify-content: flex-start;
            align-items: flex-start;
            margin-bottom: 10px;
        }
        .row label {
            font-size: 2rem;
            font-weight: bold;
            color: #000;
            width: 180px;
            text-align: left;
            letter-spacing: 1px;
        }
        .row .value {
            font-size: 2rem;
            font-weight: bold;
            color: #000;
            text-align: left;
            margin-left: 20px;
        }
        .deductions-title {
            text-align: center;
            font-size: 2.2rem;
            font-weight: bold;
            margin-top: 30px;
            margin-bottom: 10px;
        }
        .deductions-table {
            margin: 0 auto;
            font-size: 2rem;
            font-weight: bold;
            color: #000;
            width: 500px;
        }
        .deductions-table td {
            padding: 4px 12px;
        }
        .total-row td {
            font-weight: bold;
            font-size: 2rem;
            padding-top: 10px;
        }
        .netpay-row {
            margin-top: 40px;
            font-size: 2.2rem;
            font-weight: bold;
        }
    </style> -->
</head>
<body>
    <div class="container">
        <h1>PAYROLL PROGRAM</h1>
        <div class="row">
            <label>ID:</label>
            <span class="value">18-456-7</span>
        </div>
        <div class="row">
            <label>NAME:</label>
            <span class="value">De Guzman, Richard D.</span>
        </div>
        <div class="row">
            <label>POSITION:</label>
            <span class="value">IT Lecturer</span>
        </div>
        <div class="row">
            <label>RATE:</label>
            <span class="value">695</span>
        </div>
        <div class="row">
            <label>DAYS:</label>
            <span class="value">10</span>
        </div>
        <div class="row">
            <label>GROSS PAY:</label>
            <span class="value">6950.00</span>
        </div>
        <div class="deductions-title">DEDUCTIONS</div>
        <table class="deductions-table">
            <tr>
                <td>SSS(5%):</td>
                <td style="text-align:right;">347.50</td>
            </tr>
            <tr>
                <td>PAG-IBIG(3%):</td>
                <td style="text-align:right;">208.50</td>
            </tr>
            <tr>
                <td>PHILHEALTH(2%):</td>
                <td style="text-align:right;">139.00</td>
            </tr>
            <tr>
                <td>TAX(5%):</td>
                <td style="text-align:right;">347.50</td>
            </tr>
            <tr class="total-row">
                <td>TOTAL DEDUCTION:</td>
                <td style="text-align:right;">1042.50</td>
            </tr>
        </table>
        <div class="netpay-row">
            NET PAY:&nbsp;&nbsp;5907.50
        </div>
    </div>
</body>
</html>







<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GRC Payroll Program</title>
</head>
<body>
    <div class="container">
        <h1>GRC PAYROLL PROGRAM</h1>
        <form class="payroll-form">
            <div class="form-row">
                <label>ID NUMBER</label>
                <input type="text" value="18-456-7" readonly>
            </div>
            <div class="form-row">
                <label>LAST NAME</label>
                <input type="text" value="De Guzman" readonly>
            </div>
            <div class="form-row">
                <label>FIRST NAME</label>
                <input type="text" value="Richard" readonly>
            </div>
            <div class="form-row">
                <label>MIDDLE NAME</label>
                <input type="text" value="De Leon" readonly>
            </div>
            <div class="form-row">
                <label>POSITION</label>
                <input type="text" value="IT Lecturer" readonly>
            </div>
            <div class="form-row">
                <label>RATE</label>
                <input type="text" value="695" readonly>
            </div>
            <div class="form-row">
                <label>WORK DAYS</label>
                <input type="text" value="10" readonly>
            </div>
            <div class="form-row submit-row">
                <button type="submit">SUBMIT</button>
            </div>
        </form>
    </div>
</body>
</html>







body {
    background: #89ff89;
    font-family: Arial, Helvetica, sans-serif;
}

.container {
    background: #4fffd6;
    border: 5px solid #000;
    border-radius: 35px;
    width: 900px;
    margin: 40px auto;
    padding: 30px 40px 40px 40px;
    box-sizing: border-box;
}

h1 {
    text-align: center;
    color: #0000ff;
    font-size: 4rem;
    font-weight: bold;
    margin-bottom: 30px;
    letter-spacing: 2px;
}

.payroll-form {
    display: flex;
    flex-direction: column;
    gap: 18px;
}

.form-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 0;
}

.form-row label {
    font-size: 2.2rem;
    font-weight: bold;
    color: #000;
    width: 320px;
    text-align: left;
    letter-spacing: 1px;
}

.form-row input {
    font-size: 2rem;
    font-weight: bold;
    width: 500px;
    padding: 8px 18px;
    border: 3px solid #000;
    border-radius: 16px;
    background: #f3f3f3;
    color: #000;
    text-align: center;
    outline: none;
}

.submit-row {
    justify-content: flex-end;
    margin-top: 10px;
}

button {
    font-size: 2rem;
    font-weight: bold;
    padding: 8px 38px;
    border: 3px solid #000;
    border-radius: 16px;
    background: #eaeaea;
    color: #000;
    cursor: pointer;
    transition: background 0.2s;
}

button:hover {
    background: #d1d1d1;
}







