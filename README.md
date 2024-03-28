#Used Model

ENN Pose-Estimation Model
TFLITE Pose-Classfication Model
Description

Get a human photo by device's camera.
ENN Pose-Estimation Model Processes photo and makes human key points.
TF Lite Pose-Classification Model decide analysis key points and classifies whether a human falls down or not.
Github repository

https://github.com/lemonmungchi/ai

#To do

procedure Detect_Human_Falldown(S1, T1, S2, T2)
     if S1 == “Not Fall Down” then
          if S1 != S2 then
                if  T2 – T1 < 1 second then
                    alert(“Emergency!”)
               end-if
          end-if
     end-if
end procedure
