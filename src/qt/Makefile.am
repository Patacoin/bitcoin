include $(top_srcdir)/src/Makefile.include

AM_CPPFLAGS += -I$(top_srcdir)/src \
  -I$(top_builddir)/src/qt \
  -I$(top_builddir)/src/qt/forms \
  $(PROTOBUF_CFLAGS) \
  $(QR_CFLAGS)
bin_PROGRAMS = patacoin-qt
noinst_LIBRARIES = libpatacoinqt.a
SUBDIRS = $(BUILD_TEST_QT)
DIST_SUBDIRS = test

# patacoin qt core #
QT_TS = \
  locale/patacoin_ach.ts \
  locale/patacoin_af_ZA.ts \
  locale/patacoin_ar.ts \
  locale/patacoin_be_BY.ts \
  locale/patacoin_bg.ts \
  locale/patacoin_bs.ts \
  locale/patacoin_ca_ES.ts \
  locale/patacoin_ca.ts \
  locale/patacoin_cs.ts \
  locale/patacoin_cy.ts \
  locale/patacoin_da.ts \
  locale/patacoin_de_AT.ts \
  locale/patacoin_de.ts \
  locale/patacoin_el_GR.ts \
  locale/patacoin_en.ts \
  locale/patacoin_eo.ts \
  locale/patacoin_es_CL.ts \
  locale/patacoin_es_MX.ts \
  locale/patacoin_es.ts \
  locale/patacoin_et.ts \
  locale/patacoin_eu_ES.ts \
  locale/patacoin_fa_IR.ts \
  locale/patacoin_fa.ts \
  locale/patacoin_fi.ts \
  locale/patacoin_fr_CA.ts \
  locale/patacoin_fr.ts \
  locale/patacoin_gl.ts \
  locale/patacoin_gu_IN.ts \
  locale/patacoin_he.ts \
  locale/patacoin_hi_IN.ts \
  locale/patacoin_hr.ts \
  locale/patacoin_hu.ts \
  locale/patacoin_id_ID.ts \
  locale/patacoin_it.ts \
  locale/patacoin_ja.ts \
  locale/patacoin_kk_KZ.ts \
  locale/patacoin_ko_KR.ts \
  locale/patacoin_la.ts \
  locale/patacoin_lt.ts \
  locale/patacoin_lv_LV.ts \
  locale/patacoin_ms_MY.ts \
  locale/patacoin_nb.ts \
  locale/patacoin_nl.ts \
  locale/patacoin_pam.ts \
  locale/patacoin_pl.ts \
  locale/patacoin_pt_BR.ts \
  locale/patacoin_pt_PT.ts \
  locale/patacoin_ro_RO.ts \
  locale/patacoin_ru.ts \
  locale/patacoin_sk.ts \
  locale/patacoin_sl_SI.ts \
  locale/patacoin_sq.ts \
  locale/patacoin_sr.ts \
  locale/patacoin_sv.ts \
  locale/patacoin_th_TH.ts \
  locale/patacoin_tr.ts \
  locale/patacoin_uk.ts \
  locale/patacoin_vi.ts \
  locale/patacoin_vi_VN.ts \
  locale/patacoin_zh_CN.ts \
  locale/patacoin_zh_TW.ts

QT_FORMS_UI = \
  forms/aboutdialog.ui \
  forms/addressbookpage.ui \
  forms/askpassphrasedialog.ui \
  forms/coincontroldialog.ui \
  forms/editaddressdialog.ui \
  forms/intro.ui \
  forms/openuridialog.ui \
  forms/optionsdialog.ui \
  forms/overviewpage.ui \
  forms/receivecoinsdialog.ui \
  forms/receiverequestdialog.ui \
  forms/rpcconsole.ui \
  forms/sendcoinsdialog.ui \
  forms/sendcoinsentry.ui \
  forms/signverifymessagedialog.ui \
  forms/transactiondescdialog.ui

QT_MOC_CPP = \
  moc_aboutdialog.cpp \
  moc_addressbookpage.cpp \
  moc_addresstablemodel.cpp \
  moc_askpassphrasedialog.cpp \
  moc_patacoinaddressvalidator.cpp \
  moc_patacoinamountfield.cpp \
  moc_patacoingui.cpp \
  moc_patacoinunits.cpp \
  moc_clientmodel.cpp \
  moc_coincontroldialog.cpp \
  moc_coincontroltreewidget.cpp \
  moc_csvmodelwriter.cpp \
  moc_editaddressdialog.cpp \
  moc_guiutil.cpp \
  moc_intro.cpp \
  moc_macdockiconhandler.cpp \
  moc_macnotificationhandler.cpp \
  moc_monitoreddatamapper.cpp \
  moc_notificator.cpp \
  moc_openuridialog.cpp \
  moc_optionsdialog.cpp \
  moc_optionsmodel.cpp \
  moc_overviewpage.cpp \
  moc_paymentserver.cpp \
  moc_qvalidatedlineedit.cpp \
  moc_qvaluecombobox.cpp \
  moc_receivecoinsdialog.cpp \
  moc_receiverequestdialog.cpp \
  moc_recentrequeststablemodel.cpp \
  moc_rpcconsole.cpp \
  moc_sendcoinsdialog.cpp \
  moc_sendcoinsentry.cpp \
  moc_signverifymessagedialog.cpp \
  moc_splashscreen.cpp \
  moc_trafficgraphwidget.cpp \
  moc_transactiondesc.cpp \
  moc_transactiondescdialog.cpp \
  moc_transactionfilterproxy.cpp \
  moc_transactiontablemodel.cpp \
  moc_transactionview.cpp \
  moc_walletframe.cpp \
  moc_walletmodel.cpp \
  moc_walletview.cpp

patacoin_MM = \
  macdockiconhandler.mm \
  macnotificationhandler.mm

QT_MOC = \
  patacoin.moc \
  intro.moc \
  overviewpage.moc \
  rpcconsole.moc

QT_QRC_CPP = qrc_patacoin.cpp
QT_QRC = patacoin.qrc

PROTOBUF_CC = paymentrequest.pb.cc
PROTOBUF_H = paymentrequest.pb.h
PROTOBUF_PROTO = paymentrequest.proto

patacoin_QT_H = \
  aboutdialog.h \
  addressbookpage.h \
  addresstablemodel.h \
  askpassphrasedialog.h \
  patacoinaddressvalidator.h \
  patacoinamountfield.h \
  patacoingui.h \
  patacoinunits.h \
  clientmodel.h \
  coincontroldialog.h \
  coincontroltreewidget.h \
  csvmodelwriter.h \
  editaddressdialog.h \
  guiconstants.h \
  guiutil.h \
  intro.h \
  macdockiconhandler.h \
  macnotificationhandler.h \
  monitoreddatamapper.h \
  notificator.h \
  openuridialog.h \
  optionsdialog.h \
  optionsmodel.h \
  overviewpage.h \
  paymentrequestplus.h \
  paymentserver.h \
  qvalidatedlineedit.h \
  qvaluecombobox.h \
  receivecoinsdialog.h \
  receiverequestdialog.h \
  recentrequeststablemodel.h \
  rpcconsole.h \
  sendcoinsdialog.h \
  sendcoinsentry.h \
  signverifymessagedialog.h \
  splashscreen.h \
  trafficgraphwidget.h \
  transactiondesc.h \
  transactiondescdialog.h \
  transactionfilterproxy.h \
  transactionrecord.h \
  transactiontablemodel.h \
  transactionview.h \
  walletframe.h \
  walletmodel.h \
  walletmodeltransaction.h \
  walletview.h

RES_ICONS = \
  res/icons/add.png \
  res/icons/address-book.png \
  res/icons/patacoin.ico \
  res/icons/patacoin.png \
  res/icons/patacoin_testnet.ico \
  res/icons/patacoin_testnet.png \
  res/icons/clock1.png \
  res/icons/clock2.png \
  res/icons/clock3.png \
  res/icons/clock4.png \
  res/icons/clock5.png \
  res/icons/configure.png \
  res/icons/connect0_16.png \
  res/icons/connect1_16.png \
  res/icons/connect2_16.png \
  res/icons/connect3_16.png \
  res/icons/connect4_16.png \
  res/icons/debugwindow.png \
  res/icons/edit.png \
  res/icons/editcopy.png \
  res/icons/editpaste.png \
  res/icons/export.png \
  res/icons/filesave.png \
  res/icons/history.png \
  res/icons/key.png \
  res/icons/lock_closed.png \
  res/icons/lock_open.png \
  res/icons/overview.png \
  res/icons/qrcode.png \
  res/icons/quit.png \
  res/icons/receive.png \
  res/icons/remove.png \
  res/icons/send.png \
  res/icons/synced.png \
  res/icons/toolbar.png \
  res/icons/toolbar_testnet.png \
  res/icons/transaction0.png \
  res/icons/transaction2.png \
  res/icons/tx_inout.png \
  res/icons/tx_input.png \
  res/icons/tx_output.png \
  res/icons/tx_mined.png

patacoin_QT_CPP = \
  aboutdialog.cpp \
  patacoin.cpp \
  patacoinaddressvalidator.cpp \
  patacoinamountfield.cpp \
  patacoingui.cpp \
  patacoinunits.cpp \
  clientmodel.cpp \
  csvmodelwriter.cpp \
  guiutil.cpp \
  intro.cpp \
  monitoreddatamapper.cpp \
  notificator.cpp \
  optionsdialog.cpp \
  optionsmodel.cpp \
  qvalidatedlineedit.cpp \
  qvaluecombobox.cpp \
  rpcconsole.cpp \
  signverifymessagedialog.cpp \
  splashscreen.cpp \
  trafficgraphwidget.cpp

if ENABLE_WALLET
patacoin_QT_CPP += \
  addressbookpage.cpp \
  addresstablemodel.cpp \
  askpassphrasedialog.cpp \
  coincontroldialog.cpp \
  coincontroltreewidget.cpp \
  editaddressdialog.cpp \
  openuridialog.cpp \
  overviewpage.cpp \
  paymentrequestplus.cpp \
  paymentserver.cpp \
  receivecoinsdialog.cpp \
  receiverequestdialog.cpp \
  recentrequeststablemodel.cpp \
  sendcoinsdialog.cpp \
  sendcoinsentry.cpp \
  transactiondesc.cpp \
  transactiondescdialog.cpp \
  transactionfilterproxy.cpp \
  transactionrecord.cpp \
  transactiontablemodel.cpp \
  transactionview.cpp \
  walletframe.cpp \
  walletmodel.cpp \
  walletmodeltransaction.cpp \
  walletview.cpp
endif

RES_IMAGES = \
  res/images/about.png \
  res/images/splash.png \
  res/images/splash_testnet.png

RES_MOVIES = $(wildcard res/movies/spinner-*.png)

patacoin_RC = res/patacoin-qt-res.rc

libpatacoinqt_a_CPPFLAGS = $(AM_CPPFLAGS) $(QT_INCLUDES) \
  -I$(top_srcdir)/src/qt/forms $(QT_DBUS_INCLUDES)
libpatacoinqt_a_SOURCES = $(patacoin_QT_CPP) $(patacoin_QT_H) $(QT_FORMS_UI) \
  $(QT_QRC) $(QT_TS) $(PROTOBUF_PROTO) $(RES_ICONS) $(RES_IMAGES) $(RES_MOVIES)

nodist_libpatacoinqt_a_SOURCES = $(QT_MOC_CPP) $(QT_MOC) $(PROTOBUF_CC) \
  $(PROTOBUF_H) $(QT_QRC_CPP)

BUILT_SOURCES = $(nodist_libpatacoinqt_a_SOURCES)

#Generating these with a half-written protobuf header leads to wacky results.
#This makes sure it's done.
$(QT_MOC): $(PROTOBUF_H)
$(QT_MOC_CPP): $(PROTOBUF_H)

if TARGET_DARWIN
  libpatacoinqt_a_SOURCES += $(patacoin_MM)
endif
if TARGET_WINDOWS
  libpatacoinqt_a_SOURCES += $(patacoin_RC)
endif
#

# patacoin-qt binary #
patacoin_qt_CPPFLAGS = $(AM_CPPFLAGS) $(QT_INCLUDES) \
  -I$(top_srcdir)/src/qt/forms
patacoin_qt_SOURCES = patacoin.cpp
patacoin_qt_LDADD = libpatacoinqt.a $(LIBpatacoin_SERVER)
if ENABLE_WALLET
patacoin_qt_LDADD += $(LIBpatacoin_WALLET)
endif
patacoin_qt_LDADD += $(LIBpatacoin_CLI) $(LIBpatacoin_COMMON) $(LIBLEVELDB) $(LIBMEMENV) \
  $(BOOST_LIBS) $(QT_LIBS) $(QT_DBUS_LIBS) $(QR_LIBS) $(PROTOBUF_LIBS) $(BDB_LIBS)

# forms/foo.h -> forms/ui_foo.h
QT_FORMS_H=$(join $(dir $(QT_FORMS_UI)),$(addprefix ui_, $(notdir $(QT_FORMS_UI:.ui=.h))))

#locale/foo.ts -> locale/foo.qm
QT_QM=$(QT_TS:.ts=.qm)

.PHONY: FORCE
.SECONDARY: $(QT_QM)

patacoinstrings.cpp: FORCE
	$(MAKE) -C $(top_srcdir)/src qt/patacoinstrings.cpp

translate: patacoinstrings.cpp $(QT_FORMS_UI) $(QT_FORMS_UI) $(patacoin_QT_CPP) $(patacoin_QT_H) $(patacoin_MM)
	@test -n $(LUPDATE) || echo "lupdate is required for updating translations"
	@QT_SELECT=$(QT_SELECT) $(LUPDATE) $^ -locations relative -no-obsolete -ts locale/patacoin_en.ts

$(QT_QRC_CPP): $(QT_QRC) $(QT_QM) $(QT_FORMS_H) $(RES_ICONS) $(RES_IMAGES) $(RES_MOVIES) $(PROTOBUF_H)
	@cd $(abs_srcdir); test -f $(RCC) && QT_SELECT=$(QT_SELECT) $(RCC) -name patacoin -o $(abs_builddir)/$@ $< || \
	  echo error: could not build $@
	$(SED) -i.bak -e '/^\*\*.*Created:/d' $@ && rm $@.bak
	$(SED) -i.bak -e '/^\*\*.*by:/d' $@ && rm $@.bak

CLEANFILES = $(BUILT_SOURCES) $(QT_QM) $(QT_FORMS_H) *.gcda *.gcno
