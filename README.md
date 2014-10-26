OSHWDEM-TT-Express
==================

Todoterreno con prisas para la OSHWDEM 2014


// http://hobbyking.com/hobbyking/store/__26267__133RPM_Brushed_Motor_w_75_1_Gearbox.html
// http://hobbyking.com/hobbyking/store/__25072__1_10_Crawler_90mm_Wheel_Tyre_12mm_Hex_2pc_.html

Faltaría ESC, servo para dirección, Arduino y BT

module motor(){
    color ("Silver")
    rotate ([0,90,0])  {
        cylinder(r = 25/2, h = 54, center = true, $fn=48);
        translate ([0,0,35]) cylinder(r = 16.5/2, h = 4, center = true, $fn=48);
        translate ([0,0,6]) cylinder(r = 4/2, h = 66, center = true, $fn=48);
    }
}

module wheel(){
    color ("DimGray")
    rotate ([0,90,0])    
    cylinder(r = 90/2, h = 38, center = true, $fn=48);
}

rotate ([0,90,0])    {
    cylinder(r = 4/2, h = 100, center = true, $fn=48);
    translate ([0,0,25])    cylinder(r = 16.5/2, h = 4, center = true, $fn=48);
}

translate ([70,0,0])    wheel();
translate ([-70,0,0])    wheel();
translate ([-10,25/2+4,0])    motor();

translate ([0,150,0]){
rotate ([0,90,0]){
    cylinder(r = 4/2, h = 100, center = true, $fn=48);
    translate ([0,0,25])    cylinder(r = 16.5/2, h = 4, center = true, $fn=48);
}
translate ([70,0,0])    wheel();
translate ([-70,0,0])    wheel();
translate ([-10,25/2+4,0]) motor();
}

    
