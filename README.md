# ChordRunner

ChordRunner is a simple real-time loop generator with a separate melody layer and
drum layer. The hand motion is captured via a Leap Motion and transformed into
musical parameters that define the loop content.

Project was realized in an Ubuntu operating system with the linux version of the
[leapmotion](https://puredatajapan.info/?page_id=1514) external. I am aware of a [windows](https://github.com/jmmmp/Pd_Leapmotion_win) version as well. I did not test the code on
windows but it does not contain any linux exclusive content. In theory it should work on
windows as well.

For the linux version you need Pure Data. You can install it using apt-get or compiling it
from the source code following the instructions [here](https://puredata.info/).
Afterwards you need to compile the leapmotion external. For this you need the
[LeapSDK](https://developer.leapmotion.com/) from the Leap Motion website. You also need to install [flext](https://grrrr.org/research/software/flext/). For all of these
steps you can follow [this tutorial](https://philtgun.me/2017/02/04/leap-synth/).
After making sure that Pure Data, LeapSDK and leapmotion external working you can
open the ChordRunner.pd patch on Pure Data.
Note: If you are using the vanilla distribution of Pd you will need to install the cup
external through the Find Externals menu inside Pure Data.

[To see ChordRunner in action you can see this short demo video.](https://www.youtube.com/watch?v=6OPpMwqAPyk&feature=youtu.be)
