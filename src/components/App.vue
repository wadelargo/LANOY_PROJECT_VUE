  <template>

    <div class="main-container">
      <div class="main-nav">
          <Nav />
      </div>

      <div class="container">
        <div class="side">
          <Side />
        </div>

        <div class="content">
          <Content />
        </div>
      </div>
    
     

    </div>
  
  </template>

  <script>
  import Nav from './components/Nav.vue';
  import Side from './components/Side.vue';
  import Content from './components/content.vue';

  export default{
    components: {
      Nav,
      Side,
      Content

    }
  }

  </script>

  <style>
  *{
    margin: 0;
    padding: 0;
    overflow: hidden;
  }

  .main-container{
    background-color: white;
    width: 100%;
    height: 100vh;
    
  }

  .side{
    background-color: rgb(187, 187, 183);
    width: 9%;
    height: 100vh;
  }

  .container{
    display: flex;
  }

  .content{
    background-color: rgba(170, 170, 178, 0.389);
    /* padding: 10px; */
    width: 100%;
    height: 100vh;
    display: flex;
    text-align: center;
    justify-content: center;
    align-items: center;
  }

  </style>