
Trying to run Caffe on EC2

Complete instructions to configure an Ubuntu EC2 g-instance up to have Caffe and ffmpeg which is enough to create deep dream inception videos.  These are my notes, take them for what they are.
 
Good for applying:
 * https://github.com/google/deepdream (haven't run this yet)
 * https://github.com/graphific/DeepDreamVideo (this one's scripts need a bit of care)


To use:
 *  Start an EC2 instance 
   * A g instance such as g2.8xlarge instance (cheaper if you go for spot instances)
   * OS: Ubuntu Server 14.04 LTS (HVM), SSD Volume Type - ami-5189a661 (Amazon's current offering)
   * Must go to instance details to make sure you have more storage (I used 64GB)
 *  Follow the many steps in steps.txt

![Example image](exampleImg.jpeg)

Credit to the original deep dream inception authors:
 * Alexander Mordvintsev
 * Christopher Olah
 * Mike Tyka
 * http://googleresearch.blogspot.ch/2015/06/inceptionism-going-deeper-into-neural.html

To the Caffe project:
 * http://caffe.berkeleyvision.org
 * BVLC AMI: https://github.com/BVLC/caffe/wiki/Caffe-on-EC2-Ubuntu-14.04-Cuda-7

An alternative is a ready to go Docker image (I have not tested this):
 * https://github.com/VISIONAI/clouddream


And to the authors of the referenced guides (credited where they are used in steps.txt).

See also:
 * https://photos.google.com/share/AF1QipPX0SCl7OzWilt9LnuQliattX4OUCj_8EP65_cTVnBmS1jnYgsGQAieQUc1VQWdgQ?key=aVBxWjhwSzg2RjJWLWRuVFBBZEN1d205bUdEMnhB
 * https://github.com/BVLC/caffe/wiki/Install-Caffe-on-EC2-from-scratch-(Ubuntu,-CUDA-7,-cuDNN)
 * https://github.com/graphific/DeepDreamVideo (this one's scripts need a bit of care)
 * https://github.com/samim23/DeepDreamAnim (this one was slow for me, and did not re-assemble frames in correct order)
 * http://rocknrollnerd.github.io/ml/2015/05/27/leopard-sofa.html
 * https://news.ycombinator.com/item?id=9749660
 * http://www.win-vector.com/blog/2015/06/neural-net-image-salad-again-with-code/
 * https://www.reddit.com/r/deepdream/
 * https://news.ycombinator.com/item?id=9865398

