Requirements:

caffe 64 bit: download from http://thirdeyesqueegee.com/deepdream/2015/07/19/running-googles-deep-dream-on-windows-with-or-without-cuda-the-easy-way/

anaconda python

openCV

cmake

boost: need to compile boost python in 64 bit using visual studio 2013

dlib: need to compile 64 bit version. had problems with exceptions, needed to compile directly from .vcproj
dlib model url: http://sourceforge.net/projects/dclib/files/dlib/v18.10/shape_predictor_68_face_landmarks.dat.bz2

caffe model taken from:
https://github.com/AlfredXiangWu/face_verification_experiment/find/master
