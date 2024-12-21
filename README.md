@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Set a base font size and family */
html {
  font-size: 16px;
  font-family: "Poppins", serif;
  scroll-behavior: smooth;
}

/* Apply a consistent style to the body */
body {
  color: #333;
  background-color: #f9f9f9; 
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  line-height: 1;
}


/* footer {
  text-align: center;
  width: 100%;
  padding: 1rem 0;
  background-color: #333;
  color: #fff;
} */


.top{
  width: 100%;
  height: 80px;
  background-color: #EAF6F8;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 50px;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
  
}
.top-right{
     width: 130px;
     height: 70px;
     background-image: url('../images/logo.png');
     background-position: center;
     background-size: cover;
     background-repeat: no-repeat;
     border-radius: 20% 0% 20% 0%;
     border: 2px solid #007bff;
}
.top-left{
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
.top-left .top-user-id{
  width: 80px;
  height: 40px;
  border:  1px solid #007bff;
  border-radius: 5px;
  border-top: 4px solid #007bff;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding: 0;
}

.top-left .top-user-id p:nth-child(1){
  font-size: 12px;
  font-weight: 600;
  color: #007bff;
}
.top-left .top-user-id p:nth-child(2){
  font-size: 15px;
  font-weight: 700;
  color:#000;
}
.top-user-money{
  width: 90px;
  height: 38px;
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 4px;
}
.top-user-money div{
  color: #fff;
  width: 25px;
  height: 25px;
  font-weight: 600;
  background-color: #029D02;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.top-user-money h5{
    color: #029D02;
}
.top-add-money{
  position: relative;
  width: 40px;
  height: 40px;
  text-decoration: none;
  font-size: 18px;
  
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #609CC1;
  border-radius: 4px;
}
.top-add-money i{
  width: 22px;
  height: 22px;
  background-color: #fff;
  border-radius: 50%;
  color: #609CC1;
  display: flex;
  justify-content: center;
  align-items: center;
}
.top-add-money .top-circle{
  position: absolute;
  top: -5px;
  right:-5px;
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background-color: #029D02;
  border: 2px solid #EAF6F8;
}
/* For Chrome, Safari, Edge, and Opera */
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  -webkit-appearance: none;
  margin: 0;
}


/* Add responsiveness */

/* @media (min-width: 576px ) and (max-width: 746){
  body {
      width: 100%;
  }
} */
@media (max-width: 768px) {
  .container {
      width: 100%;
  }
}



@media (min-width:0px) and (max-width:576px) {
  .top{
  max-width: 100%;
  padding: 10px;
  box-sizing: border-box;
  }
}
@media (min-width:576px) and (max-width:768px) {
  .top{
  max-width: 100%;
 padding: 10px;
  box-sizing: border-box;
  }
}
