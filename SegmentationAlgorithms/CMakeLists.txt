SET(	SEGMENTATION_ALGORITHMS_SRC
	SegmentationAlgorithm.cpp
	PlanarSegmentation.cpp
)

ADD_LIBRARY(SegmentationAlgorithms SHARED ${SEGMENTATION_ALGORITHMS_SRC})
INCLUDE_DIRECTORIES(${PROJECT_SOURCE_DIR})
