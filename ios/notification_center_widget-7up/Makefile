TARGET := iphone:clang:latest:7.0
@@KILL_RULE@@

include @@THEOS@@/makefiles/common.mk

BUNDLE_NAME = @@PROJECTNAME@@

@@PROJECTNAME@@_FILES = @@PROJECTNAME@@ViewController.m
@@PROJECTNAME@@_FRAMEWORKS = UIKit CoreGraphics
@@PROJECTNAME@@_PRIVATE_FRAMEWORKS = SpringBoardUIServices
@@PROJECTNAME@@_CFLAGS = -fobjc-arc
@@PROJECTNAME@@_INSTALL_PATH = /Library/WeeLoader/Plugins

include $(THEOS_MAKE_PATH)/bundle.mk
