# Face Tracking using Commodity Depth Cameras

The aim of this project is to construct a method to track a user’s
face using commodity depth cameras. A precise tracking algorithm
allows a person to easily generate a high quality 3D model of one’s
face. It also can be used to get the pose of a person’s head with
respect to the starting frame of reference. A main obstacle that
prevents one to write a generic tracking algorithm is that different
commodity depth cameras have their own SDKs. Developing a
generic program that works on almost every camera is challenging.
This project aims to solve the above problems by developing an
algorithm that finds the pose of a person’s head from RGBD video
using an open-source framework that can be ported to work on all
widely used commodity depth cameras.
