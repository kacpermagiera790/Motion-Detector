# Motion-Detector
Simple motion-detector-hud-system written in C++

bool  engineOn = false;
bool detect = false;
bool checkArea = false;
bool showTriangle = false;
color triangleColor = COLOR_NONE;
float distance = 0.0f
float maxRange = 40.0f
float flatRange = 35.0f

void loop()
{
if(cameraON && checkArea)
{
    if(distance < maxRange)
    detect = true;
    if(checkArea >= flatRange)
    showTriangle = true;
    if(detect)
{
    showTriangle = true;
    triangleColor = COLOR_DARK_YELLOW;
}
}
}
 
