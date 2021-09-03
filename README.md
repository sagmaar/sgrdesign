<style>
  :root{

    --primary-dark: #090B47;

    --secondary: #003E8C;

    --secondary-ash: #54595F;

    --text: #7A7A7A;

    --accent: #090B47;

    --eb9ef96: #056EA3;

    --807b8dd: #06B3C9;

    --white: #ECFFFF;

    --light-grey: #B4B4B4;

    --white-gr: #B4FFE0;

    --purple-red: #A1024B;

    --green: #05A348;

    --white2: #EBFFF7;

    --white3: #FFE1EF;

    --blue-lighter: #1ABCFF;

    --blue-light: #009EDE;

    --blue-dark: #007EB0;

    --primary-font-family: "Poppins";

    --primary-font-weight: 600;

    --secondary-font-family: "Poppins";

    --secondary-font-weight: 400;

    --text-font-family: "Poppins";

    --text-font-weight: 400;

    --accent-font-family: "Poppins";

    --accent-font-weight: 500;

    --d773951-font-family: "Poppins";

    --small-font-size: 13px;

    --medium-font-weight: 500;

    font-family:  Sans-serif;

    --center: center;

    --10all: 10px 10px 10px 10px;

  }

*{

  margin:0;

  padding:0;

  list-style:none;

  text-decoration: none;

}

a{

  color: var(--white);

}



  section.sgfeat{

    background: var(--primary-dark);

    font: var(--primary-font-family);

    font-weight: var(--text-font-weight);

    color: var(--white);

    text-align: var(--center);

    padding: 10px;

  }

  .sgcardcon{

    width: 80%;

    margin-left: auto;

    margin-right: auto;

    padding: 25px 20px 25px 20px;

    border: 1px solid var(--blue-dark);

    border-radius: 12px 12px 12px 12px ;

    background: var(--secondary);

    margin-top: 25px;

  }

  .sgcardcon:hover{

    background: var(--blue-light);

  }

  .sgcardcon-head{

    text-align: var(--center);

    padding: 15px;

  }

  .sgcardcon-info{

    text-align:  justify;

    font-size: var(--small-font-size);

    text-align: var(--center);

    padding: 10px;

    line-height: 1.9;

  }

  .sgrprojects{

    padding: 25px;

    text-align: var(--center);

    padding:10px;

  }

  .sgrprojectcont{

    width: 80%;

    margin-left: auto;

    margin-right: auto;

    background: var(--blue-lighter);

    border-radius: var(--10all);

    color: var(--white3);

    text-align: var(--center);

    padding:15px;

    margin-bottom: 20px;

  }

  .sgrprojectcont:hover{

    background: var(--secondary);

  }

  .sgrprojectcont p{

    text-align: left;

    font-weight: var(--medium-font-weight);

    padding:10px;

  }

  .sgrprojectcont a{

    padding: var(--10all);

    background: var(--green);

    color: var(--white);

    padding:10px;

    text-decoration: none;

  }

  .sgrtop{

    background: linear-gradient(-45deg, var(--green), var(--blue-light), var(--primary-dark));

    color: white;

    line-height: 2;

    padding:5px;

    background-size: 200%, 200%;

    margin-top: px;

    animation: gradient 1s ease infinite;

  }

#logobar{

  color: var(--white);

  padding: 20px;

  position: fixed;

  display: block;

  background: var(--secondary);

  width:100%;

  margin-bottom: 20px;

}

#logobar h2{

  float:left;

}

#logobar #show{

  background: transparent;

  border:none;

  color: var(--white);

  line-height: 1.2;

  font-weight: bolder;

  font-size: 24px;

  transform: rotate(90deg);

  float: right;

  margin-right: 50px;

}



#logobar #close{

  background: none;

  border:none;

  color: red;

  line-height: 1.2;

  font-weight: bolder;

  font-size: 26px;

  float: right;

  margin-right: 20px;

}

#navlist{

  display:none;

  width:90%;

  margin-top:30px;



}

#navlist ul li{

  padding: 5px;

}

#navlist ul li a{

  display: block;

  padding: 10px;

  text-align: center;

  font-weight: bold;

}

#navlist ul li a:hover{

  border-bottom: 3px solid var(--blue-lighter);

  color: var(--white);

  padding: 10px;

}

#navlist ul li a:active{

  border-bottom: 3px solid var(--blue-light);

  color: var(--white);

  padding: 10px;

}

.hire{

  padding: 10px;

  background: var(--white);

  color: var(--primary-dark);

  font-weight: bold;

  border: 0.1px solid black;

  border-radius:100px;

}

.hire:hover{

  background: var(--secondary);

  color: var(--white);

  padding: 10px;

  font-weight: bold;

  text-align: center;

  border: 2px solid var(--primary-dark);

  border-radius: 100px;

}

.sgservice{

  text-align: center;

  margin-bottom: 100px;

}

.sgservice h2{

  padding:10px;

  margin-top:100px;

}

.sgservice .sgservcard{

  width: 80%;

  margin-left: auto;

  margin-right: auto;

  margin-top:60px;

  padding: 10px;

  line-height: 1.7;

  box-shadow: 2px 5px 30px #000;

  border-radius: 15px;

}



.team{

  margin-left: auto;

  margin-right: auto;

  text-align: center;

  margin-top: 100px;

  margin-bottom: 100px;

}



.sgteam{

  padding:10px;

  margin-top: 80px;

  line-height: 1.6;

}

.sgteam a:hover{

  background: var(--blue-lighter);

}

.sgteam img{

  border-radius: 100%;

  width: 150px;

  border: 3px solid red;



}

.sociallist a{

  padding: 8px;

  border-radius: 100%;

  background: var(--secondary);

  margin-left: 20px;

  text-align:center;

  font-weight: bolder;

  font-size: 20px;

  line-height: 3;

}

.profile{

  background: var(--secondary);

  color: var(--white);

  padding: 10px;

  border-radius: 100px;

}



  @@keyframes gradient{

    0%{

      background-position: 0% 50%;

    }

    50%{

      background-position: 100% 50%;

    }

    100%{

      background-position: 0% 50%;

    }

  }

</style>



<section id="logobar">

  <h2 id="logo"> SGRDESIGNz </h2>

  <button type="button" id="show" onclick="Display()"> ||| </button>

  <div id="navlist" style="display:">

    <br />

    <button type="button" id="close" onclick="Hide()">X </button>

    <ul>

      <li id="HOME"><a href="#"> Home </a></li>

      <li id="HOME"><a href="#SERVICES"> Service </a></li>

      <li id="HOME"><a href="#PROJECT"> Projects </a></li>

      <li id="HOME"><a href="#TEAM"> Our Team  </a></li>

      <li id="HOME"><a href="#CLINTS"> Clients </a></li>

      <li id="HOME"><a href="#CONTACT"> Contact </a></li>

      <li id="HOME"><a href="#ABOUT"> About </a></li>

    </ul>



  </div>

  <script type="text/javascript">

    function Display(){

      document.getElementById('navlist').style.display='block';

    }

    function Hide(){

      document.getElementById('navlist').style.display='none';

    }

  </script>

</section>

<section class="sgrtop">

  <br/>

  <br/>

  <br/>

  <br/>

  <div style="text-align:left; font-weight:normal; padding: 10px; font-size: 12px;  margin-left: 10px;">

  <h2> Our Goal is to make you Happy </h2>

  <p> We will make your Application and / or Website the way you want, in lined with the Latest Modern UI Designs. We Charge less, and Develop More.....</p>

  <br />

  <br />

  <br />

  <a class="hire" href="/p/hireus.html"> HIRE US FOR YOUR PROJECT </a>

  </div>

  <br/>

  <br/>



</section>





<section class="sgservice" id="SERVICE">

  <h2> FEATURES </h2>

  <hr />

  <div class="sgservcard">

    <svg xmlns="http://www.w3.org/2000/svg" width="57.322" height="65" viewBox="0 0 57.322 60.357"><g><path d="M56.143,5H52.369V1.178a1.179,1.179,0,0,0-2.357,0V5.686l-4.928,4.942A26.958,26.958,0,0,0,7.9,49.643a27.424,27.424,0,0,0,2.493,2.209L3.9,58.344a1.179,1.179,0,1,0,1.667,1.667l6.773-6.772A27,27,0,0,0,41.642,53.2l6.814,6.813a1.179,1.179,0,1,0,1.667-1.667l-6.539-6.539a27.527,27.527,0,0,0,2.436-2.162,26.976,26.976,0,0,0,5.228-30.767A1.179,1.179,0,1,0,49.125,19.9a24.379,24.379,0,0,1,2.433,10.682A24.6,24.6,0,1,1,43.417,12.3l-4.138,4.149A18.751,18.751,0,1,0,45.71,30.582a18.688,18.688,0,0,0-4.754-12.477l4.983-5,.005,0,0,0,5.731-5.747h4.464a1.179,1.179,0,1,0,0-2.357ZM42.782,26.282a16.406,16.406,0,1,1-5.171-8.161L32.745,23a9.561,9.561,0,1,0,1.683,1.652l4.86-4.875A16.393,16.393,0,0,1,42.782,26.282Zm-16.5,4.867a1.179,1.179,0,0,0,1.667,0l4.8-4.812a7.2,7.2,0,1,1-1.688-1.647l-4.78,4.794A1.178,1.178,0,0,0,26.283,31.149Z" fill="#000"></path><circle cx="47.902" cy="15.754" r="1.179" fill="#ff0000"></circle></g></svg>

    <br /> <br />

    <h3> TRUSTED </h3>

    <p> We are trusted by Hundred of clients </p>

    </br />

  </div>

  <div class="sgservcard">

    <svg xmlns="http://www.w3.org/2000/svg" width="57.322" height="65" viewBox="0 0 57.322 60.357"><g><path d="M56.143,5H52.369V1.178a1.179,1.179,0,0,0-2.357,0V5.686l-4.928,4.942A26.958,26.958,0,0,0,7.9,49.643a27.424,27.424,0,0,0,2.493,2.209L3.9,58.344a1.179,1.179,0,1,0,1.667,1.667l6.773-6.772A27,27,0,0,0,41.642,53.2l6.814,6.813a1.179,1.179,0,1,0,1.667-1.667l-6.539-6.539a27.527,27.527,0,0,0,2.436-2.162,26.976,26.976,0,0,0,5.228-30.767A1.179,1.179,0,1,0,49.125,19.9a24.379,24.379,0,0,1,2.433,10.682A24.6,24.6,0,1,1,43.417,12.3l-4.138,4.149A18.751,18.751,0,1,0,45.71,30.582a18.688,18.688,0,0,0-4.754-12.477l4.983-5,.005,0,0,0,5.731-5.747h4.464a1.179,1.179,0,1,0,0-2.357ZM42.782,26.282a16.406,16.406,0,1,1-5.171-8.161L32.745,23a9.561,9.561,0,1,0,1.683,1.652l4.86-4.875A16.393,16.393,0,0,1,42.782,26.282Zm-16.5,4.867a1.179,1.179,0,0,0,1.667,0l4.8-4.812a7.2,7.2,0,1,1-1.688-1.647l-4.78,4.794A1.178,1.178,0,0,0,26.283,31.149Z" fill="#000"></path><circle cx="47.902" cy="15.754" r="1.179" fill="#ff0000"></circle></g></svg>

    <br /> <br />

    <h3> TIMING </h3>

    <p> We always finish the Project on the stated time / date. </p>

    <br />

  </div>

  <div class="sgservcard">

    <svg xmlns="http://www.w3.org/2000/svg" width="57.322" height="65" viewBox="0 0 57.322 60.357"><g><path d="M56.143,5H52.369V1.178a1.179,1.179,0,0,0-2.357,0V5.686l-4.928,4.942A26.958,26.958,0,0,0,7.9,49.643a27.424,27.424,0,0,0,2.493,2.209L3.9,58.344a1.179,1.179,0,1,0,1.667,1.667l6.773-6.772A27,27,0,0,0,41.642,53.2l6.814,6.813a1.179,1.179,0,1,0,1.667-1.667l-6.539-6.539a27.527,27.527,0,0,0,2.436-2.162,26.976,26.976,0,0,0,5.228-30.767A1.179,1.179,0,1,0,49.125,19.9a24.379,24.379,0,0,1,2.433,10.682A24.6,24.6,0,1,1,43.417,12.3l-4.138,4.149A18.751,18.751,0,1,0,45.71,30.582a18.688,18.688,0,0,0-4.754-12.477l4.983-5,.005,0,0,0,5.731-5.747h4.464a1.179,1.179,0,1,0,0-2.357ZM42.782,26.282a16.406,16.406,0,1,1-5.171-8.161L32.745,23a9.561,9.561,0,1,0,1.683,1.652l4.86-4.875A16.393,16.393,0,0,1,42.782,26.282Zm-16.5,4.867a1.179,1.179,0,0,0,1.667,0l4.8-4.812a7.2,7.2,0,1,1-1.688-1.647l-4.78,4.794A1.178,1.178,0,0,0,26.283,31.149Z" fill="#000"></path><circle cx="47.902" cy="15.754" r="1.179" fill="#ff0000"></circle></g></svg>

    <br /> <br />

    <h3> MODERN UI </h3>

    <p> Making a stylish / classical Modern Design </p>

    <br />

  </div>

  <div class="sgservcard">

    <svg xmlns="http://www.w3.org/2000/svg" width="57.322" height="65" viewBox="0 0 57.322 60.357"><g><path d="M56.143,5H52.369V1.178a1.179,1.179,0,0,0-2.357,0V5.686l-4.928,4.942A26.958,26.958,0,0,0,7.9,49.643a27.424,27.424,0,0,0,2.493,2.209L3.9,58.344a1.179,1.179,0,1,0,1.667,1.667l6.773-6.772A27,27,0,0,0,41.642,53.2l6.814,6.813a1.179,1.179,0,1,0,1.667-1.667l-6.539-6.539a27.527,27.527,0,0,0,2.436-2.162,26.976,26.976,0,0,0,5.228-30.767A1.179,1.179,0,1,0,49.125,19.9a24.379,24.379,0,0,1,2.433,10.682A24.6,24.6,0,1,1,43.417,12.3l-4.138,4.149A18.751,18.751,0,1,0,45.71,30.582a18.688,18.688,0,0,0-4.754-12.477l4.983-5,.005,0,0,0,5.731-5.747h4.464a1.179,1.179,0,1,0,0-2.357ZM42.782,26.282a16.406,16.406,0,1,1-5.171-8.161L32.745,23a9.561,9.561,0,1,0,1.683,1.652l4.86-4.875A16.393,16.393,0,0,1,42.782,26.282Zm-16.5,4.867a1.179,1.179,0,0,0,1.667,0l4.8-4.812a7.2,7.2,0,1,1-1.688-1.647l-4.78,4.794A1.178,1.178,0,0,0,26.283,31.149Z" fill="#000"></path><circle cx="47.902" cy="15.754" r="1.179" fill="#ff0000"></circle></g></svg>

    <br /> <br />

    <h3> CHEAP </h3>

    <p> You'll spend less for a Project, as we charge Less</p>

    <br />

  </div>

</section>



<section class="sgfeat" id="SERVICES">

  <h2> WHAT DO WE DO </h2>

  <div class="sgcardcon">

    <svg xmlns="http://www.w3.org/2000/svg" width="73.036" height="35" viewBox="0 0 73.036 69.086"><path d="M36.518,41.278a13.9,13.9,0,0,0-8.746,24.705,1.516,1.516,0,0,0,.193.154,13.878,13.878,0,0,0,17.106,0,1.506,1.506,0,0,0,.192-.154,13.9,13.9,0,0,0-8.745-24.705m0,24.956a10.985,10.985,0,0,1-6.1-1.845,6.605,6.605,0,0,1,12.208,0,10.99,10.99,0,0,1-6.1,1.845M34,55.183a2.273,2.273,0,1,1,2.274,2.272A2.277,2.277,0,0,1,34,55.183m10.851,7.24a9.37,9.37,0,0,0-4.49-4.152,5.125,5.125,0,1,0-8.046.164,9.355,9.355,0,0,0-4.139,3.988,11.051,11.051,0,1,1,16.675,0M13.9,0A13.9,13.9,0,0,0,5.158,24.705a1.506,1.506,0,0,0,.192.154,13.879,13.879,0,0,0,17.107,0,1.506,1.506,0,0,0,.192-.154A13.9,13.9,0,0,0,13.9,0m0,24.956a10.985,10.985,0,0,1-6.1-1.845,6.606,6.606,0,0,1,12.208,0,10.989,10.989,0,0,1-6.1,1.845M11.39,13.905a2.273,2.273,0,1,1,2.274,2.272,2.276,2.276,0,0,1-2.274-2.272m10.851,7.241a9.377,9.377,0,0,0-4.49-4.153,5.126,5.126,0,1,0-8.046.165,9.355,9.355,0,0,0-4.139,3.988,11.051,11.051,0,1,1,16.675,0M59.132,0a13.9,13.9,0,0,0-8.745,24.706,1.591,1.591,0,0,0,.192.153,13.878,13.878,0,0,0,17.106,0,1.439,1.439,0,0,0,.192-.154A13.9,13.9,0,0,0,59.132,0m0,24.956a10.98,10.98,0,0,1-6.1-1.845,6.606,6.606,0,0,1,12.208,0,10.994,10.994,0,0,1-6.1,1.845M56.618,13.905a2.273,2.273,0,1,1,2.274,2.272,2.277,2.277,0,0,1-2.274-2.272m10.851,7.241a9.375,9.375,0,0,0-4.489-4.153,5.126,5.126,0,1,0-8.047.164,9.357,9.357,0,0,0-4.139,3.989,11.052,11.052,0,1,1,16.675,0M20.11,48.728A1.426,1.426,0,0,1,18.255,50.9l-.017-.014a1.426,1.426,0,0,1,1.854-2.168l.018.015m-2.783-2.86a1.426,1.426,0,1,1-2.2,1.817l0,0a1.426,1.426,0,0,1,2.183-1.836l.018.022M15.015,42.6a1.427,1.427,0,0,1-2.463,1.443v0A1.425,1.425,0,1,1,15,42.569l.018.026m-2.96-7.437a1.426,1.426,0,0,1-1.075,1.706,1.5,1.5,0,0,1-.317.036,1.428,1.428,0,0,1-1.39-1.112l-.007-.029a1.427,1.427,0,1,1,2.789-.6m1.183,3.834a1.428,1.428,0,0,1-.8,1.853,1.447,1.447,0,0,1-.525.1,1.427,1.427,0,0,1-1.326-.9l0-.007a1.427,1.427,0,0,1,2.646-1.067l.008.021m41.716,9.889a1.425,1.425,0,0,1-.156,2l-.017.014a1.426,1.426,0,0,1-1.854-2.167l.016-.015a1.425,1.425,0,0,1,2.011.168m6.708-10.7a1.43,1.43,0,0,1-.54,2.755,1.4,1.4,0,0,1-.525-.1,1.42,1.42,0,0,1-.8-1.844l.008-.021a1.426,1.426,0,0,1,1.856-.789m-3.925,7.493a1.43,1.43,0,1,1-2.028.192l.018-.022a1.426,1.426,0,0,1,2.01-.17m4.945-11.606a1.421,1.421,0,0,1,1.087,1.688l-.006.031a1.426,1.426,0,1,1-2.781-.633v0a1.428,1.428,0,0,1,1.7-1.084M60,42.083a1.435,1.435,0,1,1-1.975.513l.016-.027A1.429,1.429,0,0,1,60,42.083m3.05-12.238a1.428,1.428,0,0,1-.078,2.853l-.08,0a1.422,1.422,0,0,1-1.346-1.5v-.005a1.426,1.426,0,0,1,1.5-1.346M45.394,2.579a1.427,1.427,0,0,1-.877,2.715l-.015,0a1.427,1.427,0,0,1,.878-2.715l.014,0m-4.383-1.03a1.426,1.426,0,0,1-.229,2.834,1.525,1.525,0,0,1-.233-.019,1.426,1.426,0,1,1,.424-2.821l.038.006M36.5,1.226a1.427,1.427,0,0,1,0,2.854H36.48a1.427,1.427,0,0,1-.014-2.853H36.5M29.4,3.537a1.425,1.425,0,0,1-.952,1.779,1.462,1.462,0,0,1-.42.064A1.426,1.426,0,0,1,27.6,2.592l.02-.006a1.426,1.426,0,0,1,1.779.951M33.636,2.8a1.429,1.429,0,0,1-1.184,1.637l-.031,0a1.679,1.679,0,0,1-.212.015A1.427,1.427,0,0,1,32,1.619l.211,1.411L32,1.619A1.425,1.425,0,0,1,33.636,2.8M11.463,30.88a1.426,1.426,0,0,1-1.075,1.706,1.445,1.445,0,0,1-.317.035A1.428,1.428,0,0,1,8.68,31.51c0-.005,0-.024-.006-.029a1.427,1.427,0,0,1,2.789-.6" fill="#fff"></path></svg>

    <br /> <br /> <h3 class="sgcardcon-hed">

        <span> WEBSITE DESIGN </span>

    </h3>

    <p class="sgcardcon-info"> We design a website of any Category be it School, Business, Workshop, Personal Profile, Company, Personal Project etc.</p>

  </div>

  <div class="sgcardcon">

    <svg xmlns="http://www.w3.org/2000/svg" width="57.322" height="35" viewBox="0 0 57.322 60.357"><g><path d="M56.143,5H52.369V1.178a1.179,1.179,0,0,0-2.357,0V5.686l-4.928,4.942A26.958,26.958,0,0,0,7.9,49.643a27.424,27.424,0,0,0,2.493,2.209L3.9,58.344a1.179,1.179,0,1,0,1.667,1.667l6.773-6.772A27,27,0,0,0,41.642,53.2l6.814,6.813a1.179,1.179,0,1,0,1.667-1.667l-6.539-6.539a27.527,27.527,0,0,0,2.436-2.162,26.976,26.976,0,0,0,5.228-30.767A1.179,1.179,0,1,0,49.125,19.9a24.379,24.379,0,0,1,2.433,10.682A24.6,24.6,0,1,1,43.417,12.3l-4.138,4.149A18.751,18.751,0,1,0,45.71,30.582a18.688,18.688,0,0,0-4.754-12.477l4.983-5,.005,0,0,0,5.731-5.747h4.464a1.179,1.179,0,1,0,0-2.357ZM42.782,26.282a16.406,16.406,0,1,1-5.171-8.161L32.745,23a9.561,9.561,0,1,0,1.683,1.652l4.86-4.875A16.393,16.393,0,0,1,42.782,26.282Zm-16.5,4.867a1.179,1.179,0,0,0,1.667,0l4.8-4.812a7.2,7.2,0,1,1-1.688-1.647l-4.78,4.794A1.178,1.178,0,0,0,26.283,31.149Z" fill="#fff"></path><circle cx="47.902" cy="15.754" r="1.179" fill="#fff"></circle></g></svg>

    <br /> <br /> <h3 class="sgcardcon-hed">

        <span> Android Application </span>

    </h3>

    <p class="sgcardcon-info"> We Design Android Application for School, Business and the rest... </p>

  </div>



  <div class="sgcardcon">

      <svg xmlns="http://www.w3.org/2000/svg" width="57.322" height="35" viewBox="0 0 57.322 60.357"><g><path d="M56.143,5H52.369V1.178a1.179,1.179,0,0,0-2.357,0V5.686l-4.928,4.942A26.958,26.958,0,0,0,7.9,49.643a27.424,27.424,0,0,0,2.493,2.209L3.9,58.344a1.179,1.179,0,1,0,1.667,1.667l6.773-6.772A27,27,0,0,0,41.642,53.2l6.814,6.813a1.179,1.179,0,1,0,1.667-1.667l-6.539-6.539a27.527,27.527,0,0,0,2.436-2.162,26.976,26.976,0,0,0,5.228-30.767A1.179,1.179,0,1,0,49.125,19.9a24.379,24.379,0,0,1,2.433,10.682A24.6,24.6,0,1,1,43.417,12.3l-4.138,4.149A18.751,18.751,0,1,0,45.71,30.582a18.688,18.688,0,0,0-4.754-12.477l4.983-5,.005,0,0,0,5.731-5.747h4.464a1.179,1.179,0,1,0,0-2.357ZM42.782,26.282a16.406,16.406,0,1,1-5.171-8.161L32.745,23a9.561,9.561,0,1,0,1.683,1.652l4.86-4.875A16.393,16.393,0,0,1,42.782,26.282Zm-16.5,4.867a1.179,1.179,0,0,0,1.667,0l4.8-4.812a7.2,7.2,0,1,1-1.688-1.647l-4.78,4.794A1.178,1.178,0,0,0,26.283,31.149Z" fill="#fff"></path><circle cx="47.902" cy="15.754" r="1.179" fill="#fff"></circle></g></svg>

    <br /> <br /> <h3 class="sgcardcon-hed">

        <span> Graphic Design </span>

    </h3>

    <p class="sgcardcon-info"> We make all kind of Graphics, walpapers, I.D Cards, logo, Banner, Seal, Invitations, Posters, Letter headings etc.  </p>

  </div>



  <div class="sgcardcon">

    <svg xmlns="http://www.w3.org/2000/svg" width="57.322" height="35" viewBox="0 0 57.322 60.357"><g><path d="M56.143,5H52.369V1.178a1.179,1.179,0,0,0-2.357,0V5.686l-4.928,4.942A26.958,26.958,0,0,0,7.9,49.643a27.424,27.424,0,0,0,2.493,2.209L3.9,58.344a1.179,1.179,0,1,0,1.667,1.667l6.773-6.772A27,27,0,0,0,41.642,53.2l6.814,6.813a1.179,1.179,0,1,0,1.667-1.667l-6.539-6.539a27.527,27.527,0,0,0,2.436-2.162,26.976,26.976,0,0,0,5.228-30.767A1.179,1.179,0,1,0,49.125,19.9a24.379,24.379,0,0,1,2.433,10.682A24.6,24.6,0,1,1,43.417,12.3l-4.138,4.149A18.751,18.751,0,1,0,45.71,30.582a18.688,18.688,0,0,0-4.754-12.477l4.983-5,.005,0,0,0,5.731-5.747h4.464a1.179,1.179,0,1,0,0-2.357ZM42.782,26.282a16.406,16.406,0,1,1-5.171-8.161L32.745,23a9.561,9.561,0,1,0,1.683,1.652l4.86-4.875A16.393,16.393,0,0,1,42.782,26.282Zm-16.5,4.867a1.179,1.179,0,0,0,1.667,0l4.8-4.812a7.2,7.2,0,1,1-1.688-1.647l-4.78,4.794A1.178,1.178,0,0,0,26.283,31.149Z" fill="#fff"></path><circle cx="47.902" cy="15.754" r="1.179" fill="#fff"></circle></g></svg>

    <br /> <br /> <h3 class="sgcardcon-hed">

        <span> Blog, Themes and Templates </span>

    </h3>

    <p class="sgcardcon-info"> We set up Blogs, Blogger templates, Blogger widgets ect. AND Wordpress and Wordpress themes etc.</p>

  </div>

  <br />

  <br />

</section>





<section class="sgrprojects" id="PROJECT">

  <br />

  <br />

  <br />

  <br />

  <h2> OUR PROJECTS </h2>

  <br />

  <div class="sgrprojectcont">

    <img src="sgr.jpg" alt="" height="150" width="300px">

    <h3> Exporakey </h3>

    <p> URL: <a href="https://exporakey.com.ng"> https://exporakey.com.ng </a> </p>

    <p> Owner: SAGEER SGR </p>

    <p> Info: Website Created for Exam solution..... </p>

  </div>



  <div class="sgrprojectcont">

    <img src="sgr.jpg" alt="" height="150" width="300px">

    <h3> Exporakey </h3>

    <p> URL: <a href="https://exporakey.com.ng"> https://exporakey.com.ng </a> </p>

    <p> Owner: SAGEER SGR </p>

    <p> Info: Website Created for Exam solution..... </p>

  </div>



  <div class="sgrprojectcont">

    <img
