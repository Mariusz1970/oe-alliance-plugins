ACLOCAL_AMFLAGS = -I m4

SUBDIRS = 3GModemManager AutoBouquetsMaker BTDevicesManager DLNABrowser DLNAServer Fempa LCD4linux OnDemand OpenUitzendingGemist RemoteChannelStreamConverter StreamTV TunerServer

if HAVE_WIRELESSACCESSPOINT
SUBDIRS += WirelessAccessPoint
endif

if VUPLUS
SUBDIRS += VuplusEvent HbbTV AudioEffect
endif

if XTREND
SUBDIRS += XtrendFancontrol Blindscan XtrendRemote
endif

if ET10000
SUBDIRS += MultiTransCodingSetup
endif

if HD2400
SUBDIRS += XtrendFancontrol XtrendRemote MultiTransCodingSetup
endif

if VUDUO
SUBDIRS += VuDuoFanControl
endif

if VUUNO
SUBDIRS += FirmwareUpgrade Blindscan VuRemote
endif

if VUULTIMO
SUBDIRS += FirmwareUpgrade Blindscan VuRemote
endif

if VUSOLO2
SUBDIRS += FirmwareUpgrade VuRemote TransCodingSetup Blindscan
endif

if VUSOLOSE
SUBDIRS += FirmwareUpgrade VuRemote TransCodingSetup Blindscan
endif

if VUDUO2
SUBDIRS += FirmwareUpgrade VuRemote TransCodingSetup Blindscan
endif

if GIGABLUE
SUBDIRS += GigaBlueVFDControl Blindscan AudioEffect
endif


if HAVE_TEMPFANCONTROL
SUBDIRS += TempFanControl
endif

if GBQUADPLUS
SUBDIRS += AudioEffect TransCodingSetup
endif

if GBQUAD
SUBDIRS += AudioEffect TransCodingSetup
endif

if GB800SEPLUS
SUBDIRS += AudioEffect
endif

if GB800UEPLUS
SUBDIRS += AudioEffect
endif
