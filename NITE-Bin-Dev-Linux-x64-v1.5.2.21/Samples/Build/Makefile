include Common/CommonDefs.mak

.PHONY: all

NETPROJ = 
ifneq "$(realpath /usr/bin/gmcs)" ""
	NETPROJ += Boxes.net
endif

all: $(NETPROJ) PointServer Players CircleControl Boxes TrackPad SceneAnalysis PointViewer SingleControl Boxes.java 


.PHONY: PointServer
PointServer:
	$(MAKE) -C ../PointServer

.PHONY: Players
Players:
	$(MAKE) -C ../Players

.PHONY: Boxes.net
Boxes.net:
	$(MAKE) -C ../Boxes.net

.PHONY: CircleControl
CircleControl:
	$(MAKE) -C ../CircleControl

.PHONY: Boxes
Boxes:
	$(MAKE) -C ../Boxes

.PHONY: TrackPad
TrackPad:
	$(MAKE) -C ../TrackPad

.PHONY: SceneAnalysis
SceneAnalysis:
	$(MAKE) -C ../SceneAnalysis

.PHONY: PointViewer
PointViewer:
	$(MAKE) -C ../PointViewer

.PHONY: SingleControl
SingleControl:
	$(MAKE) -C ../SingleControl

.PHONY: Boxes.java
Boxes.java:
	$(MAKE) -C ../Boxes.java
