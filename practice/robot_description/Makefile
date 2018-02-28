URDF=urdf/pan_tilt.urdf

.PHONY: clean

all: check graph

check:
	check_urdf ${URDF}

graph:
	urdf_to_graphiz ${URDF}


clean:
	rm -f *.gv *.pdf
