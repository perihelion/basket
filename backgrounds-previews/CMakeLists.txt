
include_directories(${KDE4_INCLUDES} ${KDE4_INCLUDE_DIR} ${QT_INCLUDES} )


########### install files ###############

install(FILES  abstract.png  	alien-artifact.png  	basket-title.png  	green-curves.png  	light.png  	painting.png  	pens.png  	pins.png  	rainbow-balls.png  	rounds-line.png  	strings.png  	todo.png  	working.png DESTINATION ${DATA_INSTALL_DIR}/basket/backgrounds/previews)



#original Makefile.am contents follow:

#backgroundspreviewsdir = $(kde_datadir)/basket/backgrounds/previews
#backgroundspreviews_DATA = \
#	abstract.png \
#	alien-artifact.png \
#	basket-title.png \
#	green-curves.png \
#	light.png \
#	painting.png \
#	pens.png \
#	pins.png \
#	rainbow-balls.png \
#	rounds-line.png \
#	strings.png \
#	todo.png \
#	working.png
