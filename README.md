# Pothole Detection using Nvidia Tao and DeepStream
- This is our winning submission for the 20-hour Nvidia Hack in [AI Hack 2022](https://ai-hack-tunisia.com/)
- This is a collaboration between me, [Mohamed Ali Mimouni](https://github.com/MedAliMimouni) and [Saif Eddine Layouni](https://github.com/saiflayouni)
- We took the [Building Real-Time Video AI Applications](https://courses.nvidia.com/courses/course-v1:DLI+S-IV-01+V1/) course
from Nvidia DLI to learn about TAO and DeppStream then we proceeded to use them for our idea.
- Our [presentation](https://github.com/MelekElloumi/Pothole-Detection-Nvidia-AI-Hack-2022/blob/main/presentation_pdf.pdf)
- We used Nvidia's TrafficCamNet and applied transfer learning with TAO to make it detect potholes in images of streets then
we supplied it to Deepstream so it applies it in real-time on footage from cars front camera.

![imgur](https://i.imgur.com/LAdZMtV.png)

- We achieved 57% training accuracy, but it's overfitting and it needs more work for it to be deployable.
