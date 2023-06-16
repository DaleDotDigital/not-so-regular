# not-so-regular
A home for useful regular expressions I have discovered or created.

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Expression</th>
      <th>Note</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Alphanumeric</td>
      <td>^[a-zA-Z0-9]*$ </td>
      <td></td>
    </tr>
    <tr>
      <td>Email</td>
      <td>^[a-zA-Z0-9.!#$%&’*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$</td>
      <td></td>
    </tr>
    <tr>
      <td>Phone</td>
      <td>^[0-9]{6,10}$</td>
      <td></td>
    </tr>
    <tr>
      <td>South Africa ID Number</td>
      <td>^(\d\d)(0[1-9]|1[012])(0[1-9]|[12][0-9]|3[01])(\d{4})([01])(\d)(\d)(?#YYMMDDSSSSCAZ)$</td>
      <td>Use Luhn algorithm to calculate check digit (Z).</td>
    </tr>
    <tr>
      <td>URL</td>
      <td>
        /(?:(?:https?|ftp):\/\/)(?:\S+(?::\S*)?@)?(?:(?!(?:10|127)(?:\.\d{1,3}){3})(?!(?:169\.254|192\.168)(?:\.\d{1,3}){2})(?!172\.(?:1[6-9]|2\d|3[0-1])(?:\.\d{1,3}){2})(?:[1-9]\d?|1\d\d|2[01]\d|22[0-3])(?:\.(?:1?\d{1,2}|2[0-4]\d|25[0-5])){2}(?:\.(?:[1-9]\d?|1\d\d|2[0-4]\d|25[0-4]))|(?:(?:[a-z\u00a1-\uffff0-9]-*)*[a-z\u00a1-\uffff0-9]+)(?:\.(?:[a-z\u00a1-\uffff0-9]-*)*[a-z\u00a1-\uffff0-9]+)*(?:\.(?:[a-z\u00a1-\uffff]{2,}))\.?)(?::\d{2,5})?(?:[/?#]\S*)?/i
      </td>
      <td></td>
    </tr>
  </tbody>
</table>
