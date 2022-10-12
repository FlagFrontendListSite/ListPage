<template>
  <body>
    <header>
      <img src="src/assets/logo.JPG" width="300px" height="100px" />
      <ul>
        <button class="dropbtn"><h3>FLAG</h3></button>
        <div class="dropdown-content"></div>

        <button class="dropbtn"><h3>BORDER</h3></button>
        <div class="dropdown-content"></div>
        <div class="dropdown">
          <button class="dropbtn"><h3>ACTIVITY</h3></button>
          <div class="dropdown-content">
            <a href="#"><h3>STUDY</h3></a>
            <a href="#"><h3>PROJECT</h3></a>
          </div>
        </div>
        <button class="dropbtn"><h3>NOTICE</h3></button>
        <div class="dropdown-content">
          <a href="#"></a>
        </div>
        <li>
          <div class="search-bar">
            <i class="fas fa-search"></i>
            <input class="search-bar__input" type="search" placeholder="검색" />
          </div>
        </li>
      </ul>
    </header>
    <div class="container">
      <div class="box">
        <div class="myinformation">
          <div class="photo">
            <p>사진</p>
          </div>

          <div class="infobox">
            <div class="info">
              <p>이름</p>
            </div>

            <div class="info">
              <p>한 줄 소개</p>
            </div>
          </div>
        </div>

        <div class="myactivity">
          <div class="actibox">
            <div class="acti1">
              <p>2022</p>
            </div>
            <div class="acti2">
              <p>활동들</p>
            </div>

            <div class="actibox">
              <div class="acti1">
                <p>2021</p>
              </div>
              <div class="acti2">
                <p>활동들</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="box">
        <div class="botombox">
          <p>잔디</p>
        </div>
      </div>
    </div>
  </body>
</template>

<script></script>

<style scoped>
body {
  background-color: black;
  margin-top: 125px;
  width: 100%;
  height: 100%;
}

header {
  height: 65px;
  padding-bottom: 40px;
  margin-bottom: 20px;
  background: white;
  font-weight: bold;
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  position: fixed;
  top: 0;
  /* width: 100% */
  left: 0;
  right: 0;
}

.menu {
  height: 60px;
  padding-bottom: 40px;
  margin-bottom: 20px;
  background: white;
  font-weight: bold;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  position: fixed;
  top: 0;
  /* width: 100% */
  left: 0;
  right: 0;
}

ul {
  display: flex;
}
li {
  margin: 30px;
  list-style-type: none;
}

.container {
  margin: 0;
  padding: 0;
  width: 98vw;
  height: 143vh;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  margin-right: 2px;
  margin-left: 2px;

  border: 2px groove black;
}

.box {
  display: flex;
  flex-direction: column;
  width: 47vw;
  height: 143vh;
  border: 2px groove black;
}

.myinformation {
  display: flex;
  width: 46vw;
  height: 57vh;
  border: 2px groove rgb(62, 61, 61);
  margin: 10px;
  justify-content: space-evenly;
  align-items: center;
  margin-right: 2px;
  margin-left: 2px;
  background-color: rgb(62, 61, 61);
}

.titlebox {
  width: 40vw;
  height: 15vh;
  background-color: black;
  color: white;
  border: 2px groove white;
}

.photo {
  width: 20%;
  height: 113px;
  background-color: rgb(62, 61, 61);
  color: white;
  border: 3px groove gray;
  font-size: 15px;
}

.ph {
  width: 5vw;
  height: 5vh;
}

.infobox {
  width: 30vw;
  height: 20vh;
  background-color: rgb(62, 61, 61);
  color: white;
  border: 1px groove gray;
}

.info {
  width: 92%;
  height: 9vh;
  background-color: rgb(62, 61, 61);
  color: white;
  border: 3px groove gray;
  align-content: space-evenly;
  font-size: 15px;
}

.myactivity {
  display: flex;
  width: 46vw;
  height: 85vh;
  border: 2px groove rgb(46, 46, 46);
  background-color: rgb(46, 46, 46);
  margin: 10px;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
}

.actibox {
  width: 85%;
  height: 130px;
  background-color: rgb(46, 46, 46);
  color: white;
  border: 2px groove gray;
  justify-content: space-evenly;
  align-items: center;
}

.acti1 {
  width: 99%;
  height: 30px;
  background-color: rgb(46, 46, 46);
  color: white;
  border: 2px groove white;
  justify-content: space-evenly;
  align-items: center;
  font-size: 14px;
}

.acti2 {
  width: 99%;
  height: 91px;
  background-color: rgb(46, 46, 46);
  color: white;
  border: 2px groove white;
  justify-content: space-evenly;
  align-items: center;
  font-size: 14px;
}

.ground {
  display: flex;
  width: 46vw;
  height: 122vh;
  border: 2px groove black;
  margin: 10px;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
}

.botombox {
  width: 47vw;
  height: 17vh;
  border: 2px groove gray;
  justify-content: space-evenly;
  align-items: center;
  margin-right: 5px;
  margin-left: 5px;
  color: white;
  font-size: 23px;
}
</style>
