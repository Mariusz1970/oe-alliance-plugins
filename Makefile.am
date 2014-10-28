ACLOCAL_AMFLAGS = -I m4

SUBDIRS = 3GModemManager AutoBouquetsMaker BTDevicesManager DLNABrowser DLNAServer Fempa LCD4linux OnDemand OpenUitzendingGemist RemoteChannelStreamConverter StreamTV TunerServer

if HAVE_WIRELESSACCESSPOINT
SUBDIRS += WirelessAccessPoint
endif

if VUPLUS
SUBDIRS += VuplusEvent HbbTV
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
SUBDIRS += GigaBlueVFDControl Blindscan
endif


if HAVE_TEMPFANCONTROL
SUBDIRS += TempFanControl
endif

if GBQUADPLUS
SUBDIRS += TransCodingSetup
endif

if GBQUAD
SUBDIRS += TransCodingSetup
endif
