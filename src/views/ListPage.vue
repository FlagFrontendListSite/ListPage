<template>
<<<<<<< HEAD
  <div>
    <table class="board">
      <thead>
        <tr>
          <th></th>
          <th>제목</th>
          <th>작성자</th>
          <th>작성일</th>
          <th>조회수</th>
          <th>댓글</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td></td>
          <td></td>
          <td>1</td>
          <td>1</td>
          <td>1</td>
          <td>1</td>
        </tr>
      </tbody>
    </table>
  </div>
=======
  <body>
    <header>
      <img src="/src/assets/logo.JPG" width="300px" height="100px" />
      <ul>
        <button class="dropbtn"><h3>FLAG</h3></button>
        <div class="dropdown-content">
          <a href="#"></a>
        </div>

        <button class="dropbtn"><h3>BORDER</h3></button>
        <div class="dropdown-content">
          <a href="#"></a>
        </div>
        <button class="dropbtn"><h3>ACTIVITY</h3></button>
        <div class="dropdown-content">
          <a href="#">STUDY</a>
          <a href="#">PROJECT</a>
        </div>
        <button class="dropbtn"><h3>NOTICE</h3></button>
        <div class="dropdown-content">
          <a href="#"></a>
        </div>
        <li>
          <div class="search-bar">
            <i class="fas fa-search" aria-hidden="true"></i>
            <input class="search-bar__input" type="search" placeholder="검색" />
          </div>
        </li>
      </ul>
    </header>
  </body>
>>>>>>> c014e9b968c1592ba3229734fdefe1929a963e65
</template>
<script>
export default {
  components: {},
  data() {
    return {};
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {},
};
</script>

<style scoped>
<<<<<<< HEAD
.board {
  background-color: white;
}
</style>
=======
  body {
  background-color: rgba(19, 16, 16, 0.973);
  margin-top: 125px;
  width: 100%;
  height: 100%;
  align-items: center;
}
a {
  text-decoration-line: none;
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
  width: 100%;
  height: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  border: 2px groove rgba(19, 16, 16, 0.973);
}
</style>
>>>>>>> c014e9b968c1592ba3229734fdefe1929a963e65
