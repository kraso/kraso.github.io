---
layout: post
---

<h1>Nova donacija</h1>

<form method="POST" action={{ site.thankyou_page }}>
    <table style="width:100%">
        <tr>
            <th>Ime</th>
            <th><input type="text" name="Name"></th> 
        </tr>
        <tr>
            <th>Firma</th>
            <th><input type="text" name="Firm"></th> 
        </tr>
        <tr>
            <th>Znesek</th>
            <th><input type="number" name="Value"></th> 
        </tr>
    </table>
    <input type="submit" value="Doniraj">
</form>
