substprog = find_program('subst.py')

install_data('shuffler-control.svg',
    install_dir: PIXMAPS_DIR
)

install_data('shuffler-togglesticky-symbolic.svg',
    install_dir: PIXMAPS_DIR
)

shufflertargetauto = custom_target('shufflerautostart',
  output : 'shufflerdaemon-autostart.desktop',
  input : 'shufflerdaemon-autostart.desktop.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@', podir],
  install : true,
  install_dir : join_paths(sysconfdir, 'xdg', 'autostart')
)

shufflerguitargetauto = custom_target('shufflerguiautostart',
  output : 'shufflergui-autostart.desktop',
  input : 'shufflergui-autostart.desktop.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@', podir],
  install : true,
  install_dir : join_paths(sysconfdir, 'xdg', 'autostart')
)

shufflertargetw = custom_target('shufflercontrols',
  output : 'shuffler-control.desktop',
  input : 'shuffler-control.desktop.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@', podir],
  install : true,
  install_dir : join_paths(datadir, 'applications')
)

BDE_LOC=join_paths(datadir, 'budgie-extras-daemon')

BDE_FILE='windowshuffler-call_shufflergui.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-jump-down.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-jump-left.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-jump-right.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-jump-up.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tile-all.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-bottomhalf.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-bottomhalf-kb.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-bottomleft.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-bottomleft-kb.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-bottomright.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-bottomright-kb.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-lefthalf.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-lefthalf-kb.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-maximize.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-maximize-kb.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-righthalf.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-righthalf-kb.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-tophalf.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-tophalf-kb.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-topleft.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-topleft-kb.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-topright.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-tiling-topright-kb.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-resize-addcolumn.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-resize-addrow.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-resize-subtractcolumn.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-resize-subtractrow.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-resize-addrow-top.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-resize-addcolumn-left.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-resize-subtractcolumn-left.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-resize-subtractrow-top.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)

BDE_FILE='windowshuffler-toggle_stickyneighbors.bde'
shufflerbde01 = custom_target(BDE_FILE,
  output : BDE_FILE,
  input : BDE_FILE + '.in',
  command : [substprog, '@INPUT@', LIB_INSTALL_DIR, '@OUTPUT@'],
  install : true,
  install_dir : BDE_LOC
)
