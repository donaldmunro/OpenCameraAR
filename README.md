# OpenCameraAR
A fork of Mark Harmon's excellent [OpenCamera](http://opencamera.org.uk/) project. The
only changes made are to add the ability to store AR related information in a
separate YAML file with the same name as the image (it should also be possible to
save the YAML to a custom EXIV image tag in the future). AR settings  have been added to
the application settings. Currently they enable/disable saving the yaml file and also
enable or disable forcing infinite focus with no auto focus (warning auto focus
is now disabled by default).

This should serve as a monocular alternative to my
[TangoCamera](https://github.com/donaldmunro/TangoCamera) application until I get
around to porting TangoCamera to ARCode (although the point cloud facility under ARCore
will probably be much inferior to Tango due to the lack of hardware stereo
camera support). The YAML files also have the same format.
