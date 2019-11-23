# Computer Vision (CSE 6239), January Semester, 2019, KUET, Programming Assignment # 2
# Interest-Point-Matching-and-Find-Homography-Matrix
1. Find corners (at least 20) using Harris corner detector from two different images
  i. Show the found corner on the images
2. Use SIFT like or MOPS (Multiscale Oriented PatcheS) descriptor
  i. Present a graphical representation of the descriptors
3. Find matches among the key points using different (Euclidian, cosine similarity, correlation, SSD, Nearest neighbor ratio)
  i. Show the matching pair in a side-by-side image
4. Manually/Automatically chose at least four matching pair and represent and show them as Ah=0 form, where h is projective transformation / homography parameters.
5. Find homography matrix H by solving the Eqn Ah=0 using the technique of solving Homogeneous linear system or Homogeneous least square linear system.
  i. Explain the method of solving in the report as well as the solution.
6. Apply H to transform first image into a homographic transformed version using backward warping, also show all the images (first, 2nd, and the homographic transformed) side-by-side. Also show the difference between 2nd and transformed images.
