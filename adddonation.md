---
layout: default
---

<h1>Nova donacija</h1>

<form method="post" action="thankyou">
    <table style="width:100%">
        <tr>
            <th>Ime</th>
            <th><input type="text" name="name" id="name"></th> 
        </tr>
        <tr>
            <th>Firma</th>
            <th><input type="text" name="firm" id="firm"></th> 
        </tr>
        <tr>
            <th>Znesek</th>
            <th><input type="number" name="value" id="value"></th> 
        </tr>
    </table>
    <input type="submit" value="Doniraj">
</form>
