noinst_HEADERS= BaseApplication.h TutorialApplication.h
 
bin_PROGRAMS= OgreApp
 OgreApp_CPPFLAGS= -I$(top_srcdir)
 OgreApp_SOURCES= BaseApplication.cpp TutorialApplication.cpp
 OgreApp_CXXFLAGS= $(OGRE_CFLAGS) $(OIS_CFLAGS)
 OgreApp_LDADD= $(OGRE_LIBS) $(OIS_LIBS)
 
 EXTRA_DIST = bootstrap
 AUTOMAKE_OPTIONS = foreign