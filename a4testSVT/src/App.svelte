<script>
  let mobile = false;
  if(window.innerWidth < window.innerHeight){
    mobile = true;
  }
</script>
<style>
  h1{border-bottom: 1px solid black;font-weight: 10;font-size:25px;}
  src{font-weight: 10;font-size:26px;}
  main{margin-left:10%;margin-right:10%;} 
  main img{width:200px!important;height:263px!important;}
  div img{width: 100px;height:calc(263px/2);}
  main img{float: right;}
  div img{float: left;}
  .fix{margin-right:230px; }
  p{margin-right: 15px;}
  a{color:rgb(0, 123, 255);text-decoration: none;}
  a:hover{text-decoration: underline;}
  r{color:rgb(255, 0, 0);}
  cc{color:rgb(0, 183, 255)}
  top{font-weight: 10;font-size:30px;margin:5%;}
  topSub{margin:5%;}
  articleExtra{
    float: right;
    margin-right: 5%;
  }
  .mobile{
    margin-right: 5%;
    margin-left: 5%;
  }
  .grid{border-right:1px solid gray;background-color:rgb(238,238,238);padding-left:2px;padding-right:2px;}
  .gridEnd{background-color:rgb(238,238,238);padding-left:2px;padding-right:2px;}
  table{background-color:rgb(238,238,238);}
  box{float:right;width:200px;height:180px;border:1px solid black;background-color:rgb(238, 238, 238);}
  mobileBox{float:left;width:136px;height:165px;border:1px solid black;background-color:rgb(238, 238, 238);margin-right:5px;}
</style>
{#if !mobile}
  <articleExtra><p align="center">This article may be biased <br/> Discretion is advised</p></articleExtra>
    <top>
      <em>TheWestonFiles</em>
    </top><br/>
  <topSub>
    The <b>Wikipedia</b> for <em>Nerds</em>
  </topSub>
  <main>
    <h1>
      Websites banned due to Weston
    </h1>
    <box>
      <p style="margin-top:10px;" class="bc-text-align">
        <div align="center">
          <b>Extra</b><br/>
          Information
        </div>
      <p><a>&nbsp;MyEmulator</a><span>&emsp;&emsp;&nbsp;Emulator</span></p>
      <p>&nbsp;<a>Gitpod</a><span>&emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;Coding</span></p>
      <p>&nbsp;<a>Localhost</a><span>&emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Coding</span></p>
    </box>
    <p>
      Multiple websites have been banned prodominantly due to use by Weston. These websites are not closely related however and the reason for the banning of these webistes is still unclear. Wesbites that have been banned include, MyEmulator, Gitpod, and Localhost. Localhost was the most recent ban happening at 12:00 am EST on May 25, 2023. [1]
    </p>
  </main>
  {:else}
  <p align="center">
    <top><em>TheWestonFiles</em></top><br/>
    <topSub>The <b>Wikipedia</b> for <em>Nerds</em></topSub>
  </p>
  <p align="center"><em>This article has very<br/> little <b>Information</b> </em></p><br/>
  <div class="mobile">
    <h1>Websites banned due to Weston</h1>
    <mobileBox>
      <p style="margin-top:10px;" align="center" class="bc-text-align"><b>Extra</b><br/>Information</p>
      <p><a>MyEmulator:</a><span>Games</span></p>
      <p><a>Gitpod:</a><span>Coding</span></p>
      <p><a>LocalHost:</a><span>Coding</span></p>
    </mobileBox>
    <p>
      Multiple websites have been banned prodominantly due to use by Weston. These websites are not closely related however and the reason for the banning of these webistes is still unclear. Wesbites that have been banned include, MyEmulator, Gitpod, and Localhost. Localhost was the most recent ban happening at 12:00 am EST on May 25, 2023. [1]
    </p>
  </div>
{/if}