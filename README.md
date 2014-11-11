OSHWDEM-TT-Express
==================

Todoterreno con prisas para la OSHWDEM 2014
http://www.ebay.com/itm/1-10-KRT-Crawler-Chrome-Wheel-Tire-Set-90MM-K1-Boom-Racing-/201195269971?pt=Radio_Control_Parts_Accessories&hash=item2ed82c2f53
http://www.ebay.com/itm/1-10-KRT-Crawler-Chrome-Wheel-Tire-Set-90MM-K1-Boom-Racing-/201195269971?pt=Radio_Control_Parts_Accessories&hash=item2ed82c2f53


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

    http://openscad.net/#?c=Ly8gaHR0cDovL2hvYmJ5a2luZy5jb20vaG9iYnlraW5nL3N0b3JlL19fMjYyNjdfXzEzM1JQTV9CcnVzaGVkX01vdG9yX3dfNzVfMV9HZWFyYm94Lmh0bWwKLy8gaHR0cDovL2hvYmJ5a2luZy5jb20vaG9iYnlraW5nL3N0b3JlL19fMjUwNzJfXzFfMTBfQ3Jhd2xlcl85MG1tX1doZWVsX1R5cmVfMTJtbV9IZXhfMnBjXy5odG1sCgptb2R1bGUgbW90b3IoKXsKICAgIGNvbG9yICgiU2lsdmVyIikKICAgIHJvdGF0ZSAoWzAsOTAsMF0pICB7CiAgICAgICAgY3lsaW5kZXIociA9IDI1LzIsIGggPSA1NCwgY2VudGVyID0gdHJ1ZSwgJGZuPTQ4KTsKICAgICAgICB0cmFuc2xhdGUgKFswLDAsMzVdKSBjeWxpbmRlcihyID0gMTYuNS8yLCBoID0gNCwgY2VudGVyID0gdHJ1ZSwgJGZuPTQ4KTsKICAgICAgICB0cmFuc2xhdGUgKFswLDAsNl0pIGN5bGluZGVyKHIgPSA0LzIsIGggPSA2NiwgY2VudGVyID0gdHJ1ZSwgJGZuPTQ4KTsKICAgIH0KfQoKbW9kdWxlIHdoZWVsKCl7CiAgICBjb2xvciAoIkRpbUdyYXkiKQogICAgcm90YXRlIChbMCw5MCwwXSkgICAgCiAgICBjeWxpbmRlcihyID0gOTAvMiwgaCA9IDM4LCBjZW50ZXIgPSB0cnVlLCAkZm49NDgpOwp9Cgpyb3RhdGUgKFswLDkwLDBdKSAgICB7CiAgICBjeWxpbmRlcihyID0gNC8yLCBoID0gMTAwLCBjZW50ZXIgPSB0cnVlLCAkZm49NDgpOwogICAgdHJhbnNsYXRlIChbMCwwLDI1XSkgICAgY3lsaW5kZXIociA9IDE2LjUvMiwgaCA9IDQsIGNlbnRlciA9IHRydWUsICRmbj00OCk7Cn0KCnRyYW5zbGF0ZSAoWzcwLDAsMF0pICAgIHdoZWVsKCk7CnRyYW5zbGF0ZSAoWy03MCwwLDBdKSAgICB3aGVlbCgpOwp0cmFuc2xhdGUgKFstMTAsMjUvMis0LDBdKSAgICBtb3RvcigpOwoKdHJhbnNsYXRlIChbMCwxNTAsMF0pewpyb3RhdGUgKFswLDkwLDBdKXsKICAgIGN5bGluZGVyKHIgPSA0LzIsIGggPSAxMDAsIGNlbnRlciA9IHRydWUsICRmbj00OCk7CiAgICB0cmFuc2xhdGUgKFswLDAsMjVdKSAgICBjeWxpbmRlcihyID0gMTYuNS8yLCBoID0gNCwgY2VudGVyID0gdHJ1ZSwgJGZuPTQ4KTsKfQp0cmFuc2xhdGUgKFs3MCwwLDBdKSAgICB3aGVlbCgpOwp0cmFuc2xhdGUgKFstNzAsMCwwXSkgICAgd2hlZWwoKTsKdHJhbnNsYXRlIChbLTEwLDI1LzIrNCwwXSkgbW90b3IoKTsKfQoKICAgIA%3D%3D
