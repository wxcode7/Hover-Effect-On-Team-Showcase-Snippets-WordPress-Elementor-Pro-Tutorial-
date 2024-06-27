# Hover Effect On Team Showcase Snippets WordPress Elementor Pro Tutorial
"Welcome to wxcode7 Unlock your coding potential with our tutorials, tips, and project walkthroughs. Subscribe now and start mastering the art of programming!"

.container .card {
  position: relative;
  }
.container .card .box {
  position: relative;
  width: 100%;
  transition: 0.5s;
}
.container .card .box.box1 {
  position: relative;
  background: #333;
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 1;
  transform: translateY(100px);
}
.container .card:hover .box.box1 {
  transform: translateY(0);
 }
.container .card .box.box1 .content {
  opacity: 0.8;
  transition: 0.5s;
}
.container .card:hover .box.box1 .content {
  opacity: 1;
}
.container .card .box.box2 {
  position: relative;
  background: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  box-sizing: border-box;
  box-shadow: 0 20px 50px rgba(0, 0, 0, 0.8);
  transform: translateY(-125px);
}
.container .card:hover .box.box2 {
  transform: translateY(0);
   border-radius: 0;
}

