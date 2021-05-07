<template>
  <div class="invoice-box scaled" style="background: #fff">
    <div style="overflow: hidden">
      <table class="table">
        <tr class="titles">
          <th>Navn</th>
          <th>Antall</th>
          <th>Enhet</th>
          <th>Enhetspris</th>
          <th>Rabatt</th>
          <th>MVA</th>
          <th>Sum eks MVA</th>
        </tr>
        <tr id="ProductList" class="item">
          <td id="Product">
            <span id="ProuductName">Medium Hosting<span></span></span>
          </td>
          <td>
            <span id="ProductNumUnits">6<span></span></span>
          </td>
          <td>
            <span id="ProductUnit">KG<span></span></span>
          </td>
          <td><span id="ProductUnitPrice">300kr</span></td>
          <td><span id="ProductDiscount">Rabatt</span></td>
          <td><span id="ProductTax">20%</span></td>
          <td><span id="ProductCost">900 KR</span></td>
        </tr>
        <tr class="item">
          <td>
            <span id="ProuductName">Medium Hosting<span></span></span>
          </td>
          <td>
            <span id="ProductNumUnits">6<span></span></span>
          </td>
          <td>
            <span id="ProductUnit">KG<span></span></span>
          </td>
          <td><span id="ProductUnitPrice">300kr</span></td>
          <td><span id="ProductDiscount">Rabatt</span></td>
          <td><span id="ProductTax">20%</span></td>
          <td><span id="ProductCost">900 KR</span></td>
        </tr>
        <tr class="item">
          <td>
            <span id="ProuductName">Medium Hosting<span></span></span>
          </td>
          <td>
            <span id="ProductNumUnits">6<span></span></span>
          </td>
          <td>
            <span id="ProductUnit">KG<span></span></span>
          </td>
          <td><span id="ProductUnitPrice">300kr</span></td>
          <td><span id="ProductDiscount">Rabatt</span></td>
          <td><span id="ProductTax">20</span>%</td>
          <td>
            <span id="ProductCost">900</span>
            <span id="InvoiceCurrency">KR</span>
          </td>
        </tr>
        <tr class="item">
          <td>
            <span id="ProuductName">Soup<span></span></span>
          </td>
          <td>
            <span id="ProductNumUnits">6 <span></span></span>
          </td>
          <td>
            <span id="ProductUnit">Liter <span></span></span>
          </td>
          <td><span id="ProductUnitPrice">300kr</span></td>
          <td><span id="ProductDiscount">90%</span></td>
          <td><span id="ProductTax">20%</span></td>
          <td><span id="ProductCost">900 KR</span></td>
        </tr>
      </table>
    </div>
    <div class="row">
      <div class="equalHWrap eqWrap">
        <div class="equalHW eq">
          <table class="right">
            <tr>
              <td>
                <span style="display: inline-block; margin-right: 10px"
                  ><strong>Total MVA:</strong></span
                >
              </td>
              <td>
                <span id="InvoceTotalVat">202</span>
                <span id="InvoiceCurrency1">KR</span><br />
              </td>
            </tr>
            <tr>
              <td>
                <span style="display: inline-block; margin-right: 10px"
                  ><strong>Sum eks MVA:</strong></span
                >
              </td>
              <td>
                <span id="InvoiceSumExVat">900</span>
                <span id="InvoiceCurrency2">KR</span>
              </td>
            </tr>
            <tr>
              <td>
                <span style="display: inline-block; margin-right: 10px"
                  ><strong>Å betale:</strong></span
                >
              </td>
              <td>
                <span id="ProductCost">1102</span>
                <span id="InvoiceCurrency3">KR</span>
              </td>
            </tr>
          </table>
        </div>
      </div>
      <div class="center">
        <a href="https://sequra.no" style="text-decoration: none"
          >Prøv gratis fakturerings program - rett i nettleseren
          <span style="border-bottom: 1px solid #000">Sequra</span></a
        >
      </div>
    </div>
  </div>
</template>

<style>
.scaled {
  /* transform: scale(0.3); */
}
.pinch-zoom-wrapper {
  /* background: #fff !important; */
}
html,
body {
  height: 100%;
  background: #002336;
  width: 100%;
  margin: 0;
  padding: 0;
  left: 0;
  top: 0;
  font-size: 100%;
}
* {
  font-family: 'Lato', 'Helvetica Neue', 'Helvetica', Helvetica, Arial,
    sans-serif;
  color: #333447;
  line-height: 1.5;
}
/* TYPOGRAPHY */

h1 {
  font-size: 2.5rem;
}
h2 {
  font-size: 2rem;
}
h3 {
  font-size: 1.375rem;
}
h4 {
  font-size: 1.125rem;
}
h5 {
  font-size: 1rem;
}
h6 {
  font-size: 0.875rem;
}
p {
  font-size: 1.125rem;
  font-weight: 200;
  line-height: 1.8;
}
.font-light {
  font-weight: 300;
}
.font-regular {
  font-weight: 400;
}
.font-heavy {
  font-weight: 700;
}
/* POSITIONING */

.left {
  text-align: left;
}
.right {
  float: right;
  text-align: right;
}
.center {
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}
.justify {
  text-align: justify;
}
/** standard padding**/

.no-padding {
  padding: 0px;
}
.standard-padding {
  padding: 20px;
}
.standard-padding-right {
  padding-right: 20px;
}
.standard-padding-left {
  padding-left: 20px;
}
.standard-padding-right {
  padding-left: 20px;
}
.standard-padding-top {
  padding-top: 20px;
}
.standard-padding-bottom {
  padding-bottom: 20px;
}
.container {
  width: 100%;
  margin-left: auto;
  margin-right: auto;
}
.row {
  position: relative;
  width: 100%;
}
.row [class^='col'] {
  float: left;
  margin: 0.5rem 2%;
  min-height: 0.125rem;
}
.row::after {
  content: '';
  display: table;
  clear: both;
}
.hidden-sm {
  display: none;
}
.invoice-box {
  background: #ffffff;
  width: 100%;
  margin: 60px auto;
  padding: 30px;
  border: 1px solid #002336;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.15);
  font-size: 16px;
  line-height: 24px;
  color: #002336;
}
.title {
  margin-bottom: 0px;
  padding-bottom: 0px;
  margin-left: 10px;
  margin-right: 10px;
  font-weight: bold;
  border-bottom: 1px solid #8b8b8b;
  margin-bottom: 4px;
}
.infoblock {
  margin-left: 10px;
  margin-right: 10px;
  margin-top: 0px;
  padding-top: 0px;
}
.titles {
  padding-top: 4px;
  margin-top: 20px;
  background: #dcdcdc;
  font-weight: bold;
}
@media only screen and (max-width: 600px) {
  .invoice-box table tr.top table td {
    width: 100%;
    display: block;
    text-align: center;
  }
  .invoice-box table tr.information table td {
    width: 100%;
    display: block;
    text-align: center;
  }
}
/** RTL **/

.rtl {
  direction: rtl;
  font-family: 'Lato', Tahoma, 'Helvetica Neue', 'Helvetica', Helvetica, Arial,
    sans-serif;
}
.rtl table {
  text-align: right;
}
.rtl table tr td:nth-child(2) {
  text-align: left;
}
.eqWrap {
  display: flex;
}
.eq {
  padding: 10px;
}
.item:nth-of-type(odd) {
  background: #f9f9f9;
}
.item:nth-of-type(even) {
  background: #fff;
}
.equalHW {
  flex: 1;
}
.equalHM {
  width: 32%;
}
.equalHMR {
  width: 32%;
  margin-bottom: 2%;
}
table.table {
  width: 100%;
  margin-top: 20px;
  border-collapse: collapse;
}
.table th,
.table td {
  text-align: left;
  padding: 0.25em;
}
.table tr {
  border-bottom: 1px solid #ddd;
}
button:hover {
  box-shadow: 0 0 4px rgba(3, 3, 3, 0.8);
  opacity: 0.9;
}
</style>
