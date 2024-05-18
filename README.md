# codsoft-may
using html,css to create a calculator
<html>
    <head>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
        <script src="https://kit.fontawesome.com/ac42c3b1f7.js" crossorigin="anonymous"></script>
        <link rel="stylesheet" href="dillu.css">
    </head>
    <body>
        <div id="cal-body">
            <div class="input">
                <input type="text" id="display" disabled>
            </div>
            <div style="padding-top: 40px;">
                <div class="buttons">
                    <button onclick="clearDisplay()">AC</button>
                    <button onclick="appendNumber('00')">00</button>
                    <button onclick="appendNumber('.')">.</button>
                    <button onclick="setOperation('+')">+</button>
                </div>
                <div class="buttons">
                    <button onclick="appendNumber('1')">1</button>
                    <button onclick="appendNumber('2')">2</button>
                    <button onclick="appendNumber('3')">3</button>
                    <button onclick="setOperation('-')">-</button>
                </div>
                <div class="buttons">
                    <button onclick="appendNumber('4')">4</button>
                    <button onclick="appendNumber('5')">5</button>
                    <button onclick="appendNumber('6')">6</button>
                    <button onclick="setOperation('*')">*</button>
                </div>
                <div class="buttons">
                    <button onclick="appendNumber('7')">7</button>
                    <button onclick="appendNumber('8')">8</button>
                    <button onclick="appendNumber('9')">9</button>
                    <button onclick="setOperation('/')">/</button>
                </div>
                <div class="buttons">
                    <button onclick="appendNumber('0')">0</button>
                    <button onclick="appendNumber('000')">000</button>
                    <button style="width: 140px;" onclick="computeResult()">=</button> 
                </div>
            </div>
        </div>
        <script src="cal.java script"></script>
    </body>
</html>
