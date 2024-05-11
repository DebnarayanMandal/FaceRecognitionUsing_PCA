
# PRINCIPAL COMPONENT ANALISIS BASED TECHNIQUES FOR FACE RECOGNITION USING MACHINE LEARNITNG.

In the contemporary period of research, one of the major disciplines is human
facial recognition. Face recognition is unique among biometrics except that it is
multidimensional, and virtually every human faces have a similar format. Face
recognition in shifting lighting conditions in an uncontrolled setting remains a
serious difficulty. I've gathered a variety of face images. After that, I'll be able to
use feature extraction. I'm working on a face recognition system that uses KNN,
SVM, Decision Tree, and Random Forest classifiers, as well as the Principal
Component technique. The ORL set of data is intended to validate the results of
the experiments. A PCA-based facial recognition system, on the other hand, still
seems to be time-consuming and requires calculating a large number of values to
determine the eigen-vectors.
I contrast 1-dimensional Classification Technique to those other face recognition
methods like 2D PCA in this study. With exception of PCA, 2D PCA employs
two-dimensional matrix but instead of 1D vectors, which eliminates the
requirement to convert the image matrix into a vector during extracting the
features.However, the image covariance matrix is created by using original image
feature extraction. On the ORL dataset, a variety of experiments are done to test
and verify 2D PCA. 2D PCA had a greater recognition rate and accuracy than
PCA in all trials.


## Objective
The objective of using PCA (Principal Component Analysis) in a face recognition system is to reduce the dimensionality of the face images while preserving the most important information necessary for accurate recognition. Here's how PCA is typically applied in a face recognition system:

Dimensionality Reduction: Face images are typically high-dimensional, especially if they are in color or high-resolution. PCA is used to reduce the dimensionality of these images by finding a set of orthogonal axes (principal components) that capture the maximum variance in the data.

Feature Extraction: Each face image is treated as a point in a high-dimensional space. PCA transforms these points into a lower-dimensional space, where each image is represented by a vector of reduced dimensionality. These vectors are the principal components that capture the essential features of the face images.

Eigenfaces: The principal components obtained from PCA are often referred to as eigenfaces. These eigenfaces represent the directions of maximum variance in the face image dataset. They can be thought of as "generic face patterns" that capture the main variations in facial appearance across the dataset.

Recognition: During the recognition phase, a new face image is projected onto the lower-dimensional subspace spanned by the eigenfaces. This projection results in a low-dimensional representation of the new face image. By comparing this representation with those of known faces (stored in a database), the system can identify or verify the identity of the person in the new image.

Classification: The reduced-dimensional representations of face images can be used as input to classification algorithms (such as k-nearest neighbors or support vector machines) and characteristics.

Overall, the objective of using PCA in a face recognition system is to improve computational efficiency, reduce storage requirements, and enhance recognition accuracy by extracting and representing the essential features of face images in a lower-dimensional space.







## FACE COLLECTION

Before, we test the face recognition technique we need to collection of human
face images. That’s why we need to collect human face images in vary angle and
also lighting, darkness, inside home and outside home images as well. We take
a ORL dataset that have same kind of images, next I using PCA and 2D PCA on
ORL dataset to find out how to accurately work in face recognition technique.
## Result
There I discuss what kind of result and accuracy I get.
## CONCLUSION
In this research, I attempt to investigate one types of Principal Component
Technique and 1D Principal Component Technique methodologies. I also spoke
about what other people believe about PCA . I just only use ORL
dataset for find out the facial recognition. Inside my dataset have all pixel value,
then I converted all pixel values to image format than use PCA for
facial recognition with using of Eigen-faces. And training images were cropped
from each subject's original face to a smaller area ear to ear horizontally and
forehead to lips vertically. Meanwhile, the same different classification was not
found when a non-library input image was evaluated.
There, I showed a number of algorithms for face identification under uncontrolled
illumination depending on the center region of the face being considered normal,
bright, very bright, or dark. Finally, this method shows a promising and good
results but it’s still needs to be explored.