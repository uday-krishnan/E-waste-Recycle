<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #004A99;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background: #004A99;
            padding: 20px;
            border-radius: 5px;
            text-align: center;
            color: white;
            width: 600px;
        }
        h2 {
            margin-bottom: 20px;
        }
        .form-group {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }
        input, select, textarea {
            width: 48%;
            padding: 10px;
            border: none;
            border-radius: 5px;
            margin-left: 40px;
            margin-bottom: 20px;
            font-size: 16px;
            transition: all 0.3s ease-in-out;
        }
        textarea {
            width: 100%;
            height: 80px;
            resize: none;
        }
        input:focus, select:focus, textarea:focus {
            outline: 2px solid #FFA500;
            transform: scale(1.02);
        }
        .captcha {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-top: 10px;
        }
        .captcha span {
            font-size: 18px;
            margin-right: 10px;
        }
        .submit-btn {
            background: #FFA500;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.3s ease-in-out;
        }
        .submit-btn:hover {
            background: #cc8400;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Should we contact you?</h2>
        <div class="form-group">
            <input s type="text" placeholder="Name">
            <input type="text" placeholder="Company">
        </div>
        <div class="form-group">
            <input type="text" placeholder="Phone">
            <input type="email" placeholder="Email">
        </div>
        <div class="form-group">
            <select>
                <option>country</option>
                <option>Country</option>
                <option>Bahrain</option>
                <option>Bangladesh</option>
                <option>Barbados</option>
                <option>Belarus</option>
                <option>Belgium</option>
                <option>Belize</option>
                <option>Benin</option>
                <option>Bhutan</option>
                <option>Bolivia</option>
                <option>Bosnia and Herzegovina</option>
                <option>Botswana</option>
                <option>Brazil</option>
                <option>Brunei</option>
                <option>Bulgaria</option>
                <option>Burkina Faso</option>
                <option>Burundi</option>
                <option>Cabo Verde</option>
                <option>Cambodia</option>
                <option>Cameroon</option>
                <option>Canada</option>
                <option>Central African Republic</option>
                <option>Chad</option>
                <option>Chile</option>
                <option>China</option>
                <option>Colombia</option>
                <option>Comoros</option>
                <option>Congo (Brazzaville)</option>
                <option>Congo (Kinshasa)</option>
                <option>Costa Rica</option>
                <option>Croatia</option>
                <option>Cuba</option>
                <option>Cyprus</option>
                <option>Czech Republic</option>
                <option>Denmark</option>
                <option>Djibouti</option>
                <option>Dominica</option>
                <option>Dominican Republic</option>
                <option>Ecuador</option>
                <option>Egypt</option>
                <option>El Salvador</option>
                <option>Equatorial Guinea</option>
                <option>Eritrea</option>
                <option>Estonia</option>
                <option>Eswatini</option>
                <option>Ethiopia</option>
                <option>Fiji</option>
                <option>Finland</option>
                <option>France</option>
                <option>Gabon</option>
                <option>Gambia</option>
                <option>Georgia</option>
                <option>Germany</option>
                <option>Ghana</option>
                <option>Greece</option>
                <option>Grenada</option>
                <option>Guatemala</option>
                <option>Guinea</option>
                <option>Guinea-Bissau</option>
                <option>Guyana</option>
                <option>INDIA</option>
            </select>
            <select>
                <option>recycling solutions</option>
                <option>Aluminium Recycling</option>
                <option>ASR Recycling</option>
                <option>Cable Recycling</option>
                <option>Car Battery Recycling</option>
                <option>Electronics Recycling</option>
                <option>Fridge Recycling</option>
                <option>Municipal Solid Waste</option>
                <option>Service / Spare parts</option>
                <option>Tyre Recycling</option>
                <option>Various Scrap</option>
            </select>
        </div>
        <textarea placeholder="Please describe here how we may help you"></textarea>
        <div class="captcha">
            <span>2 + 11 =</span>
            <input type="text" style="width: 50px;">
        </div>
        <button class="submit-btn">CONTACT ME</button>
    </div>
</body>
</html>
