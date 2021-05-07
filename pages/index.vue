<template>
  <div class="container">
    <div
      style="
        position: fixed;
        top: 0;
        z-index: 11;
        width: 100%;
        background: #fff;
        padding: 10px;
      "
    >
      <img
        src="https://www.ababank.com/typo3conf/ext/boxmodel/Resources/Private/Templates/ABA/images/aba-web-top-logo.png"
        width="30"
        height="30"
      />
      <div>Sina testing</div>
    </div>
    <pinch-zoom>
      <div style="background: #eee">
        <img
          style="width: 100%"
          src="https://www.ababank.com/fileadmin/user_upload/PopUp_Windows/ABA_Instant_Account-Pop_up-EN.jpg"
        />
        <p>
          No branch visit and paperwork — all you need is valid Khmer National
          ID card and smartphone! Introducing ABA Instant Account – your first
          bank account that you can open in the ABA Mobile app instantly from
          anywhere and anytime. Open your Instant Account now to enjoy a safe,
          modern, and convenient banking
        </p>
        <table>
          <tr>
            <th>Company</th>
            <th>Contact</th>
            <th>Country</th>
          </tr>
          <tr>
            <td>Alfreds Futterkiste</td>
            <td>Maria Anders</td>
            <td>Germany</td>
          </tr>
          <tr>
            <td>Centro comercial Moctezuma</td>
            <td>Francisco Chang</td>
            <td>Mexico</td>
          </tr>
          <tr>
            <td>Ernst Handel</td>
            <td>Roland Mendel</td>
            <td>Austria</td>
          </tr>
          <tr>
            <td>Island Trading</td>
            <td>Helen Bennett</td>
            <td>UK</td>
          </tr>
          <tr>
            <td>Laughing Bacchus Winecellars</td>
            <td>Yoshi Tannamuri</td>
            <td>Canada</td>
          </tr>
          <tr>
            <td>Magazzini Alimentari Riuniti</td>
            <td>Giovanni Rovelli</td>
            <td>Italy</td>
          </tr>
        </table>
      </div>
    </pinch-zoom>
    <div
      style="
        position: fixed;
        bottom: 0;
        width: 100%;
        background: #ccc;
        height: 56px;
        padding-top: 15px;
      "
    >
      <button>Pay now</button>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
