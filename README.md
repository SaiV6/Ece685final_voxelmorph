# Ece685final_voxelmorph

In this study, we introduce an adaptation of the VoxelMorph framework for deformable, pairwise
medical image registration based on the work done by the original VoxelMorph project [1], with a
focus on volumetric data composed of image slices. Traditional registration methods often suffer
from computational inefficiency when applied to large datasets or intricate deformation models.
Departing from conventional approaches, we redefine registration as a function mapping input
image pairs to a deformation field aligning the images. This function is parameterized by a
reduced-size convolutional neural network (CNN), optimizing network parameters using a set of
volumetric images sliced into two-dimensional inputs. For training, we propose strategies for
utilizing slices in volumetric data, including a design for the allocation of static and moving
frames. We investigate the impact of reducing the model size, specifically the encoder-decoder
architecture (g_theta), to examine the performance achieved with fewer parameters. Our findings
underscore the potential of a more streamlined architecture for efficient medical image
registration. The choice of static and moving frames, as well as the use of volumetric slices,
demonstrates versatility in the application of VoxelMorph to various medical imaging scenarios.
Our methodology not only promises to accelerate medical image analysis and processing pipelines
but also opens avenues for novel directions in learning-based registration and its diverse
applications.
