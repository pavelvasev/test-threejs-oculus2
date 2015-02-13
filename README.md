# test-threejs-oculus2
Тест подключения OculusRift 2 к ThreeJS через WebVR

Работает в специальной версии Chrome для WebVR, которая скачивается здесь:
https://drive.google.com/folderview?id=0BzudLt22BqGRbW9WTHMtOWMzNjQ

Соединен пример http://tyrovr.com/2014/06/29/three-vr-renderer-tutorial.html
с демкой http://threejs.org/examples/#webgl_buffergeometry_uint

и еще попытка использовать positions из, но пока неуспешная
https://github.com/MozVR/vr-web-examples/blob/master/threejs-vr-boilerplate/js/VRControls.js

Что особенно хорошо что в test1.html выделена переменная
var useVrRendering = true;
Если выставить ее в false, то будет обычный рендеринг.

Павел Васев 13-02-2015



