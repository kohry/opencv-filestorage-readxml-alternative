# Simple Alertanative Code for OpenCV FileStorage.

You are reading masteringOpenCV book, and frustrated with the fact that [OpenCV3 Android SDK] has no FileStorage class in it?

This simple Kotlin code from [Android tutorial](https://developer.android.com/training/basics/network-ops/xml.html) can help you.

call parse() method in this code, and you will get a nice decent Pair<Mat, Mat> object from it. (Training Data Mat & Classes Mat).

## example
GorakgarakXMLParser.parse(context.resources.openRawResource(R.raw.svm),"TrainingData")

## otehrs..
sample training data xml for Support Vector Machine is in the same directory.

## version
- Kotlin 1.1.51
- OpenCV 3