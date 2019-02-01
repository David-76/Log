01-18 11:52:19.774  6608  6623 I AdapterState: OFF : entered 
01-18 11:52:19.774  6608  6608 I bt_btif : init
01-18 11:52:19.774  6608  6623 D AdapterProperties: Setting state to OFF
01-18 11:52:19.775  6608  6608 D bt_osi_allocation_tracker: canary initialized
01-18 11:52:19.775  6608  6626 I bt_osi_thread: run_thread: thread id 6626, thread name stack_manager started
01-18 11:52:19.777  6608  6626 I bt_stack_manager: event_init_stack is initializing the stack
01-18 11:52:19.778  6608  6626 E         : [0118/115219.778126:ERROR:config.cc(74)] config_new: unable to open file '/data/misc/bluedroid/bt_config.conf': No such file or directory
01-18 11:52:19.778  6608  6626 W bt_btif_config: init unable to load config file: /data/misc/bluedroid/bt_config.conf; using backup.
01-18 11:52:19.778  6608  6626 E         : [0118/115219.778706:ERROR:config.cc(74)] config_new: unable to open file '/data/misc/bluedroid/bt_config.bak': No such file or directory
01-18 11:52:19.778  6608  6626 W bt_btif_config: init unable to load backup; attempting to transcode legacy file.
01-18 11:52:19.778  6608  6626 E bt_btif_config_transcode: btif_config_transcode unable to load XML file '/data/misc/bluedroid/bt_config.xml': 3
01-18 11:52:19.779  6608  6626 E bt_btif_config: init unable to transcode legacy file; creating empty config.
01-18 11:52:19.780  6608  6636 I bt_osi_thread: run_thread: thread id 6636, thread name alarm_default_ca started
01-18 11:52:19.780  6608  6637 I bt_osi_thread: run_thread: thread id 6637, thread name alarm_dispatcher started
01-18 11:52:19.784  6608  6626 I bt_btif_core: btif_init_bluetooth entered
01-18 11:52:19.785  6608  6626 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
01-18 11:52:19.788  6608  6638 I bt_osi_thread: run_thread: thread id 6638, thread name bt_jni_workqueue started
01-18 11:52:19.788  6608  6626 I bt_btif_core: btif_init_bluetooth finished
01-18 11:52:19.788  6608  6626 I bt_stack_manager: event_init_stack finished
01-18 11:52:19.788  6608  6638 I bt_btif_core: run_message_loop entered
01-18 11:52:19.791  6608  6608 I bt_osi_wakelock: wakelock_set_os_callouts set to non-native
01-18 11:52:19.791  6608  6608 I bt_btif : get_profile_interface: id = socket
01-18 11:52:19.791  6608  6638 E bt_btif_storage: btif_storage_get_adapter_property: Controller not ready! Unable to return Bluetooth Address
01-18 11:52:19.791  6608  6638 E BluetoothServiceJni: adapter_properties_callback: Status 1 is incorrect
01-18 11:52:19.793  6608  6608 I bt_btif : get_profile_interface: id = sdp
01-18 11:52:19.794  6608  6638 D AdapterProperties: Name is: Xperia Z
01-18 11:52:19.794   552   552 D BluetoothManagerService: Bluetooth Adapter name changed to Xperia Z
01-18 11:52:19.795  6608  6638 D AdapterProperties: BT Class:5a020c
01-18 11:52:19.795   552   552 D BluetoothManagerService: Stored Bluetooth name: Xperia Z
01-18 11:52:19.797  6608  6608 I BluetoothAdapterService: Phone policy enabled
01-18 11:52:19.801  6608  6608 D BluetoothActiveDeviceManager: start()
01-18 11:52:19.813  6608  6608 D BluetoothAdapterService: setAdapterService() - trying to set service to com.android.bluetooth.btservice.AdapterService@3c47d13
01-18 11:52:19.814  6608  6639 D BluetoothActiveDeviceManager: onAudioDevicesAdded
01-18 11:52:19.814  6608  6639 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 1
01-18 11:52:19.814  6608  6639 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 2
01-18 11:52:19.814  6608  6639 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 15
01-18 11:52:19.814  6608  6639 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 15
01-18 11:52:19.817  6608  6608 D BluetoothAdapterService: onBind()
01-18 11:52:19.817  6608  6639 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 18
01-18 11:52:19.817  6608  6639 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 16
01-18 11:52:19.824   552   552 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
01-18 11:52:19.824   552   592 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
01-18 11:52:19.825   552   592 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
01-18 11:52:19.828  6608  6621 D BluetoothAdapterService: enable() - Enable called with quiet mode status =  false
01-18 11:52:19.828  6608  6623 I AdapterState: BLE_TURNING_ON : entered 
01-18 11:52:19.828  6608  6623 D AdapterProperties: Setting state to BLE_TURNING_ON
01-18 11:52:19.828  6608  6623 D BluetoothAdapterService: updateAdapterState() - Broadcasting state BLE_TURNING_ON to 1 receivers.
01-18 11:52:19.829   552   592 D BluetoothManagerService: MESSAGE_GET_NAME_AND_ADDRESS
01-18 11:52:19.829  6608  6623 D BluetoothAdapterService: bleOnProcessStart()
01-18 11:52:19.830  6608  6623 I AdapterProperties: init(), maxConnectedAudioDevices, default=5, propertyOverlayed=5, finalValue=5
01-18 11:52:19.832  6608  6623 D BluetoothAdapterService: bleOnProcessStart() - Make Bond State Machine
01-18 11:52:19.832   552   592 D BluetoothManagerService: Stored Bluetooth name: Xperia Z
01-18 11:52:19.833   552   592 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: OFF > BLE_TURNING_ON
01-18 11:52:19.833   552   592 D BluetoothManagerService: Sending BLE State Change: OFF > BLE_TURNING_ON
01-18 11:52:19.833  6608  6623 D BluetoothBondStateMachine: make
01-18 11:52:19.835  6608  6646 I BluetoothBondStateMachine: StableState(): Entering Off State
01-18 11:52:19.845  6608  6608 I BtGatt.JNI: classInitNative(L875): classInitNative: Success!
01-18 11:52:19.848  6608  6608 D BtGatt.DebugUtils: handleDebugAction() action=null
01-18 11:52:19.848  6608  6608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c47d13
01-18 11:52:19.851  6608  6608 I bt_btif : get_profile_interface: id = gatt
01-18 11:52:19.851  6608  6608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c47d13
01-18 11:52:19.864  6608  6608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c47d13
01-18 11:52:19.865  6608  6608 D BluetoothAdapterService: handleMessage() - Message: 2
01-18 11:52:19.865  6608  6608 D BluetoothAdapterService: handleMessage() - MESSAGE_PROFILE_SERVICE_REGISTERED
01-18 11:52:19.865  6608  6608 D BluetoothAdapterService: handleMessage() - Message: 1
01-18 11:52:19.865  6608  6608 D BluetoothAdapterService: handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
01-18 11:52:19.866  6608  6608 I bt_btif : enable: start restricted = 0
01-18 11:52:19.866  6608  6626 I bt_stack_manager: event_start_up_stack is bringing up the stack
01-18 11:52:19.867  6608  6626 I bt_core_module: module_start_up Starting module "btif_config_module"
01-18 11:52:19.867  6608  6626 I bt_core_module: module_start_up Started module "btif_config_module"
01-18 11:52:19.867  6608  6626 I bt_core_module: module_start_up Starting module "btsnoop_module"
01-18 11:52:19.867  6608  6626 I bt_core_module: module_start_up Started module "btsnoop_module"
01-18 11:52:19.867  6608  6626 I bt_core_module: module_start_up Starting module "hci_module"
01-18 11:52:19.867  6608  6626 I bt_hci  : hci_module_start_up
01-18 11:52:19.867  6608  6650 I bt_osi_thread: run_thread: thread id 6650, thread name hci_thread started
01-18 11:52:19.868  6608  6650 I bt_hci  : hci_initialize
01-18 11:52:19.868  6608  6626 D bt_hci  : hci_module_start_up starting async portion
01-18 11:52:19.869   213   213 W hwservicemanager: getTransport: Cannot find entry android.hardware.bluetooth@1.0::IBluetoothHci/default in either framework or device manifest.
01-18 11:52:19.871  6608  6650 D vndksupport: Loading /vendor/lib/hw/android.hardware.bluetooth@1.0-impl.so from current namespace instead of sphal namespace.
01-18 11:52:19.875  6608  6650 I bt_hci  : hci_initialize: IBluetoothHci::getService() returned 0xa7bea140 (local)
01-18 11:52:19.875  6608  6650 I android.hardware.bluetooth@1.0-impl: BluetoothHci::initialize()
01-18 11:52:19.877  6608  6650 D         : get_local_address: Trying /data/misc/bluetooth/bdaddr
01-18 11:52:19.877  6608  6650 D         : get_local_address: Got Factory BDA 00:eb:2d:0c:55:ea
01-18 11:52:19.877  6608  6650 I bt_vendor: ++init
01-18 11:52:19.877  6608  6650 I bt_vendor: bt-vendor : get_bt_soc_type
01-18 11:52:19.877  6608  6650 I bt_vendor: vendor.qcom.bluetooth.soc set to smd
01-18 11:52:19.877  6608  6650 I bt_vendor: vendor.qcom.bluetooth.soc not set, so using default.
01-18 11:52:19.877  6608  6650 I bt_vendor: BD Address: ea:55:0c:2d:eb:00
01-18 11:52:19.878  6608  6650 D android.hardware.bluetooth@1.0-impl: Open vendor library loaded
01-18 11:52:19.878  6608  6650 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
01-18 11:52:19.878  6608  6650 I bt_vendor: bluetooth status is on
01-18 11:52:19.878  6608  6650 I bt_vendor: bt-vendor : resetting BT status
01-18 11:52:19.878  6608  6650 W bt_vendor: Hw_config: nState = 0
01-18 11:52:19.878  6608  6650 W bt_vendor: Hw_config: nState = 1
01-18 11:52:19.878  6608  6650 I bt_vendor: bluetooth status is on
01-18 11:52:19.878  6608  6650 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
01-18 11:52:19.881  6608  6650 I bt_vendor: Done intiailizing UART
01-18 11:52:19.881  6608  6650 I bt_vendor: Done intiailizing UART
01-18 11:52:19.881  6608  6650 I bt_vendor: Bluetooth FW and transport layer are initialized
01-18 11:52:19.881  6608  6650 D android.hardware.bluetooth@1.0-impl: OnFirmwareConfigured result: 0
01-18 11:52:19.881  6608  6650 I android.hardware.bluetooth@1.0-impl: Firmware configured in 0.000s
01-18 11:52:19.881  6608  6650 I android.hardware.bluetooth@1.0-impl: OnFirmwareConfigured: lpm_timeout_ms 1000
01-18 11:52:19.882  6608  6650 I bt_vendor: __op: property_get: persist.vendor.service.bdroid.lpmcfg: all
01-18 11:52:19.882  6608  6650 D android.hardware.bluetooth@1.0-impl: low_power_mode_cb result: 0
01-18 11:52:19.882  6608  6650 D android.hardware.bluetooth@1.0-impl: OnFirmwareConfigured Calling StartLowPowerWatchdog()
01-18 11:52:19.882  6608  6650 I bt_hci  : event_finish_startup
01-18 11:52:19.882  6608  6626 I bt_core_module: module_start_up Started module "hci_module"
01-18 11:52:19.883  6608  6653 I bt_osi_thread: run_thread: thread id 6653, thread name bt_workqueue started
01-18 11:52:19.884  6608  6653 I         : [0118/115219.884053:INFO:btu_task.cc(107)] Bluetooth chip preload is complete
01-18 11:52:19.885  6608  6653 I         : [0118/115219.885243:INFO:gatt_api.cc(948)] GATT_Register 81818181-8181-8181-8181-818181818181
01-18 11:52:19.885  6608  6653 I         : [0118/115219.885548:INFO:gatt_api.cc(968)] allocated gatt_if=1
01-18 11:52:19.885  6608  6653 I         : [0118/115219.885701:INFO:gatt_api.cc(161)] GATTS_AddService
01-18 11:52:19.885  6608  6653 I         : [0118/115219.885854:INFO:gatt_api.cc(265)] GATTS_AddService: service parsed correctly, now starting
01-18 11:52:19.886  6608  6653 I         : [0118/115219.886250:INFO:gatt_api.cc(948)] GATT_Register 82828282-8282-8282-8282-828282828282
01-18 11:52:19.886  6608  6653 I         : [0118/115219.886403:INFO:gatt_api.cc(968)] allocated gatt_if=2
01-18 11:52:19.886  6608  6653 I         : [0118/115219.886525:INFO:gatt_api.cc(161)] GATTS_AddService
01-18 11:52:19.886  6608  6653 I         : [0118/115219.886647:INFO:gatt_api.cc(265)] GATTS_AddService: service parsed correctly, now starting
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_HCI : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_L2CAP : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_RFCOMM : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_AVDT : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_AVRC : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_A2D : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_BNEP : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_BTM : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_HID_HOST : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_PAN : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_SDP : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_SMP : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_HID_DEV : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_BTAPP : Level 2
01-18 11:52:19.887  6608  6653 I bt_bte  : BTE_InitTraceLevels -- TRC_BTIF : Level 2
01-18 11:52:19.888  6608  6654 I bt_osi_thread: run_thread: thread id 6654, thread name btu message loop started
01-18 11:52:19.889  6608  6655 I bt_osi_thread: run_thread: thread id 6655, thread name module_wrapper started
01-18 11:52:19.889  6608  6655 I bt_core_module: module_start_up Starting module "controller_module"
01-18 11:52:19.939  6608  6652 D bt_hci  : get_waiting_command VS event found treat it as valid 0xffff
01-18 11:52:19.940  6608  6655 E bt_hci  : read_command_complete_header: return status - 0x1
01-18 11:52:19.952  6608  6655 I bt_core_module: module_start_up Started module "controller_module"
01-18 11:52:19.952  6608  6655 W bt_osi_thread: run_thread: thread id 6655, thread name module_wrapper exited
01-18 11:52:19.953  6608  6653 W bt_btm  : btm_decode_ext_features_page: feature page 1 ignored
01-18 11:52:19.953  6608  6654 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0x6e51bf5d
01-18 11:52:19.953  6608  6654 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0x6e51bf5d 
01-18 11:52:19.953  6608  6654 I bt_stack: [INFO:gatt_api.cc(948)] GATT_Register 71caabc6-9655-a2be-f79e-743c6cf420e0
01-18 11:52:19.953  6608  6654 I bt_stack: [INFO:gatt_api.cc(968)] allocated gatt_if=3
01-18 11:52:19.974  6608  6652 D bt_hci  : get_waiting_command VS event found treat it as valid 0xffff
01-18 11:52:19.975  6608  6654 F bt_stack: [FATAL:btm_ble_gap.cc(488)] Check failed: p_vcs_cplt_params->opcode == HCI_BLE_VENDOR_CAP_OCF. 
01-18 11:52:19.975  6608  6654 F libc    : Fatal signal 6 (SIGABRT), code -6 (SI_TKILL) in tid 6654 (btu message loo), pid 6608 (droid.bluetooth)
01-18 11:52:20.061   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_WAKELOCK_ACQUIRE
01-18 11:52:20.062   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_WAIT_READ
01-18 11:52:20.062   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_CLIENT_TX
01-18 11:52:20.062   296   720 D QC-QMI  : qmi_qmux: TX/RX - RX 19 bytes on conn_id=18
01-18 11:52:20.062   296   720 D QC-QMI  : qmuxd: TX message on fd=17, to qmux_client_id=0x0, len=53
01-18 11:52:20.062   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_WAKELOCK_RELEASE
01-18 11:52:20.062   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_WAIT_POLL
01-18 11:52:20.062   316   731 D QC-QMI  : qmi_client [316] 0: Received 53 bytes on fd = 12
01-18 11:52:20.062   316   731 D QC-QMI  : qmi_service.c RX indication for conn=18, srvc=3
01-18 11:52:20.062   316   731 D QC-QMI  : Processing indication: Mesage4 ID=  81, Service ID = 3
01-18 11:52:20.062   316   731 D QC-QMI  : Client 12010300 gets indication callback
01-18 11:52:20.064  6658  6658 W crash_dump32: failed to fetch registers for thread 6608: I/O error
01-18 11:52:20.065  6658  6658 W crash_dump32: failed to fetch registers for thread 6614: I/O error
01-18 11:52:20.065  6658  6658 W crash_dump32: failed to fetch registers for thread 6615: I/O error
01-18 11:52:20.065  6658  6658 W crash_dump32: failed to fetch registers for thread 6616: I/O error
01-18 11:52:20.066  6658  6658 W crash_dump32: failed to fetch registers for thread 6617: I/O error
01-18 11:52:20.066  6658  6658 W crash_dump32: failed to fetch registers for thread 6618: I/O error
01-18 11:52:20.066  6658  6658 W crash_dump32: failed to fetch registers for thread 6619: I/O error
01-18 11:52:20.067  6658  6658 W crash_dump32: failed to fetch registers for thread 6620: I/O error
01-18 11:52:20.067  6658  6658 W crash_dump32: failed to fetch registers for thread 6621: I/O error
01-18 11:52:20.067  6658  6658 W crash_dump32: failed to fetch registers for thread 6622: I/O error
01-18 11:52:20.068  6658  6658 W crash_dump32: failed to fetch registers for thread 6623: I/O error
01-18 11:52:20.068  6658  6658 W crash_dump32: failed to fetch registers for thread 6626: I/O error
01-18 11:52:20.068  6658  6658 W crash_dump32: failed to fetch registers for thread 6627: I/O error
01-18 11:52:20.069  6658  6658 W crash_dump32: failed to fetch registers for thread 6635: I/O error
01-18 11:52:20.069  6658  6658 W crash_dump32: failed to fetch registers for thread 6636: I/O error
01-18 11:52:20.069  6658  6658 W crash_dump32: failed to fetch registers for thread 6637: I/O error
01-18 11:52:20.070  6658  6658 W crash_dump32: failed to fetch registers for thread 6638: I/O error
01-18 11:52:20.070  6658  6658 W crash_dump32: failed to fetch registers for thread 6639: I/O error
01-18 11:52:20.070  6658  6658 W crash_dump32: failed to fetch registers for thread 6640: I/O error
01-18 11:52:20.071  6658  6658 W crash_dump32: failed to fetch registers for thread 6641: I/O error
01-18 11:52:20.071  6658  6658 W crash_dump32: failed to fetch registers for thread 6645: I/O error
01-18 11:52:20.071  6658  6658 W crash_dump32: failed to fetch registers for thread 6646: I/O error
01-18 11:52:20.074  6658  6658 W crash_dump32: failed to fetch registers for thread 6647: I/O error
01-18 11:52:20.074  6658  6658 W crash_dump32: failed to fetch registers for thread 6648: I/O error
01-18 11:52:20.075  6658  6658 W crash_dump32: failed to fetch registers for thread 6649: I/O error
01-18 11:52:20.075  6658  6658 W crash_dump32: failed to fetch registers for thread 6650: I/O error
01-18 11:52:20.075  6658  6658 W crash_dump32: failed to fetch registers for thread 6652: I/O error
01-18 11:52:20.075  6658  6658 W crash_dump32: failed to fetch registers for thread 6653: I/O error
01-18 11:52:20.105  6658  6658 I crash_dump32: obtaining output fd from tombstoned, type: kDebuggerdTombstone
01-18 11:52:20.106   320   320 I /system/bin/tombstoned: received crash request for pid 6654
01-18 11:52:20.106  6658  6658 I crash_dump32: performing dump of process 6608 (target tid = 6654)
01-18 11:52:20.210  6658  6658 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
01-18 11:52:20.211  6658  6658 F DEBUG   : crDroid Version: '5.0'
01-18 11:52:20.211  6658  6658 F DEBUG   : Build fingerprint: 'Sony/C6603/C6603:5.1.1/10.7.A.0.228/58103698:user/release-keys'
01-18 11:52:20.211  6658  6658 F DEBUG   : Revision: '0'
01-18 11:52:20.211  6658  6658 F DEBUG   : ABI: 'arm'
01-18 11:52:20.211  6658  6658 F DEBUG   : pid: 6608, tid: 6654, name: btu message loo  >>> com.android.bluetooth <<<
01-18 11:52:20.211  6658  6658 F DEBUG   : signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
01-18 11:52:20.212  6658  6658 F DEBUG   : Abort message: '[FATAL:btm_ble_gap.cc(488)] Check failed: p_vcs_cplt_params->opcode == HCI_BLE_VENDOR_CAP_OCF. 
01-18 11:52:20.212  6658  6658 F DEBUG   : '
01-18 11:52:20.212  6658  6658 F DEBUG   :     r0  00000000  r1  000019fe  r2  00000006  r3  00000008
01-18 11:52:20.212  6658  6658 F DEBUG   :     r4  000019d0  r5  000019fe  r6  6440296c  r7  0000010c
01-18 11:52:20.212  6658  6658 F DEBUG   :     r8  644029a4  r9  64402df4  r10 64402998  r11 64402df0
01-18 11:52:20.212  6658  6658 F DEBUG   :     ip  00000041  sp  64402958  lr  ae77404d  pc  ae76bdbe
01-18 11:52:20.315  6658  6658 F DEBUG   : 
01-18 11:52:20.315  6658  6658 F DEBUG   : backtrace:
01-18 11:52:20.315  6658  6658 F DEBUG   :     #00 pc 0001cdbe  /system/lib/libc.so (abort+58)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #01 pc 0007b5d7  /system/lib/libchrome.so (base::debug::BreakDebugger()+10)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #02 pc 0008b2ff  /system/lib/libchrome.so (logging::LogMessage::~LogMessage()+746)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #03 pc 001464d7  /system/lib/libbluetooth.so (btm_ble_vendor_capability_vsc_cmpl_cback(tBTM_VSC_CMPL*)+78)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #04 pc 00150a5b  /system/lib/libbluetooth.so (btm_vsc_complete(unsigned char*, unsigned short, unsigned short, void (*)(tBTM_VSC_CMPL*))+38)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #05 pc 00160bd1  /system/lib/libbluetooth.so (btu_hcif_command_complete_evt_on_task(BT_HDR*, void*)+440)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #06 pc 0007c503  /system/lib/libchrome.so (base::debug::TaskAnnotator::RunTask(char const*, base::PendingTask*)+162)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #07 pc 0008e145  /system/lib/libchrome.so (base::MessageLoop::RunTask(base::PendingTask*)+324)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #08 pc 0008e37b  /system/lib/libchrome.so (base::MessageLoop::DeferOrRunPendingTask(base::PendingTask)+26)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #09 pc 0008e61f  /system/lib/libchrome.so (base::MessageLoop::DoWork()+218)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #10 pc 0008f313  /system/lib/libchrome.so (base::MessagePumpDefault::Run(base::MessagePump::Delegate*)+98)
01-18 11:52:20.315  6658  6658 F DEBUG   :     #11 pc 0008df2f  /system/lib/libchrome.so (base::MessageLoop::RunHandler()+62)
01-18 11:52:20.316  6658  6658 F DEBUG   :     #12 pc 000a1cad  /system/lib/libchrome.so (base::RunLoop::Run()+80)
01-18 11:52:20.316  6658  6658 F DEBUG   :     #13 pc 00161075  /system/lib/libbluetooth.so (btu_message_loop_run(void*)+188)
01-18 11:52:20.316  6658  6658 F DEBUG   :     #14 pc 001b17f1  /system/lib/libbluetooth.so (work_queue_read_cb(void*)+52)
01-18 11:52:20.316  6658  6658 F DEBUG   :     #15 pc 001b03ab  /system/lib/libbluetooth.so (run_reactor(reactor_t*, int)+218)
01-18 11:52:20.316  6658  6658 F DEBUG   :     #16 pc 001b02a5  /system/lib/libbluetooth.so (reactor_start(reactor_t*)+44)
01-18 11:52:20.316  6658  6658 F DEBUG   :     #17 pc 001b1443  /system/lib/libbluetooth.so (run_thread(void*)+142)
01-18 11:52:20.316  6658  6658 F DEBUG   :     #18 pc 00064a63  /system/lib/libc.so (__pthread_start(void*)+22)
01-18 11:52:20.316  6658  6658 F DEBUG   :     #19 pc 0001dfd5  /system/lib/libc.so (__start_thread+32)
01-18 11:52:21.003   552   585 I ActivityManager: Showing crash dialog for package com.android.bluetooth u0
01-18 11:52:21.005   320   320 E /system/bin/tombstoned: Tombstone written to: /data/tombstones/tombstone_44
01-18 11:52:21.047   552   584 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.stats.service.DropBoxEntryAddedReceiver
01-18 11:52:21.047   552   584 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.chimera.GmsIntentOperationService$PersistentTrustedReceiver
01-18 11:52:21.061   552   590 I BootReceiver: Copying /data/tombstones/tombstone_44 to DropBox (SYSTEM_TOMBSTONE)
01-18 11:52:21.107   291  1127 D SurfaceFlinger: duplicate layer name: changing Application Error: com.android.bluetooth to Application Error: com.android.bluetooth#2
01-18 11:52:21.112   552   552 D BluetoothManagerService: BluetoothServiceConnection, disconnected: com.android.bluetooth.btservice.AdapterService
01-18 11:52:21.112   552   592 E BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED(1)
01-18 11:52:21.112   552   592 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 7 receivers.
01-18 11:52:21.112   552  1437 I ActivityManager: Process com.android.bluetooth (pid 6608) has died: psvc PER 
01-18 11:52:21.113   552  1437 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.gatt.GattService in 1000ms
01-18 11:52:21.113   552  1437 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
01-18 11:52:21.114   552   587 W libprocessgroup: kill(-6608, 9) failed: No such process
01-18 11:52:21.132   552  2673 W Adreno-EGL: <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
01-18 11:52:21.132   552   584 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.stats.service.DropBoxEntryAddedReceiver
01-18 11:52:21.132   552   584 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.chimera.GmsIntentOperationService$PersistentTrustedReceiver
01-18 11:52:21.160   552   587 W libprocessgroup: kill(-6608, 9) failed: No such process
01-18 11:52:21.161   552  2673 D vndksupport: Loading /vendor/lib/hw/gralloc.msm8960.so from current namespace instead of sphal namespace.
01-18 11:52:21.200   552   587 W libprocessgroup: kill(-6608, 9) failed: No such process
01-18 11:52:21.201   552   587 I libprocessgroup: Successfully killed process cgroup uid 1002 pid 6608 in 87ms
01-18 11:52:21.225   552   585 W Looper  : Slow dispatch took 103ms android.ui h=android.view.Choreographer$FrameHandler c=android.view.Choreographer$FrameDisplayEventReceiver@54bdc73 m=0
01-18 11:52:21.225   259   259 I Zygote  : Process 6608 exited due to signal (6)
01-18 11:52:21.232   648   648 I android.anim.lf: type=1400 audit(0.0:475): avc: denied { call } for scontext=u:r:system_server:s0 tcontext=u:r:init:s0 tclass=binder permissive=1
01-18 11:52:21.313   552   592 D BluetoothManagerService: MESSAGE_RESTART_BLUETOOTH_SERVICE
01-18 11:52:21.325   291   364 W SurfaceFlinger: Attempting to set client state on removed layer: Surface(name=375c0a6 Application Error: com.android.bluetooth)/@0x94e2e83 - animation-leash#0
01-18 11:52:21.325   291   364 W SurfaceFlinger: Attempting to destroy on removed layer: Surface(name=375c0a6 Application Error: com.android.bluetooth)/@0x94e2e83 - animation-leash#0
01-18 11:52:21.646   552   586 I ActivityManager: Start proc 6669:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
01-18 11:52:21.648  6669  6669 I Zygote  : seccomp disabled by setenforce 0
01-18 11:52:21.681  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:21.781  1347  1374 I chatty  : uid=0(root) /system/bin/mpdecision identical 2 lines
01-18 11:52:21.831  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:21.846  6669  6669 D BluetoothOppFileProvider: Initialized
01-18 11:52:21.883  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:21.894  6669  6669 V AdapterServiceConfig: Adding HeadsetService
01-18 11:52:21.897  6669  6669 V AdapterServiceConfig: Adding A2dpService
01-18 11:52:21.898  6669  6669 V AdapterServiceConfig: Adding HidHostService
01-18 11:52:21.898  6669  6669 V AdapterServiceConfig: Adding HealthService
01-18 11:52:21.898  6669  6669 V AdapterServiceConfig: Adding PanService
01-18 11:52:21.898  6669  6669 V AdapterServiceConfig: Adding GattService
01-18 11:52:21.898  6669  6669 V AdapterServiceConfig: Adding BluetoothMapService
01-18 11:52:21.901  6669  6669 V AdapterServiceConfig: Adding AvrcpTargetService
01-18 11:52:21.903  6669  6669 V AdapterServiceConfig: Adding HidDeviceService
01-18 11:52:21.909  6669  6669 V AdapterServiceConfig: Adding BluetoothOppService
01-18 11:52:21.912  6669  6669 V AdapterServiceConfig: Adding BluetoothPbapService
01-18 11:52:21.931  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:21.959  6669  6669 I         : [0118/115221.959645:INFO:com_android_bluetooth_btservice_AdapterService.cpp(630)] hal_util_load_bt_library loaded HAL: btinterface=0x562ca234, handle=0xe2192a41
01-18 11:52:21.962  6669  6669 D BluetoothAdapterService: onCreate()
01-18 11:52:21.974  6669  6669 D AdapterState: make() - Creating AdapterState
01-18 11:52:21.977  6669  6669 I bt_btif : init
01-18 11:52:21.977  6669  6669 D bt_osi_allocation_tracker: canary initialized
01-18 11:52:21.981  6669  6698 I AdapterState: OFF : entered 
01-18 11:52:21.981  6669  6698 D AdapterProperties: Setting state to OFF
01-18 11:52:21.983  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:21.983  6669  6699 I bt_osi_thread: run_thread: thread id 6699, thread name stack_manager started
01-18 11:52:21.984  6669  6699 I bt_stack_manager: event_init_stack is initializing the stack
01-18 11:52:21.987  6669  6699 E         : [0118/115221.987141:ERROR:config.cc(74)] config_new: unable to open file '/data/misc/bluedroid/bt_config.conf': No such file or directory
01-18 11:52:21.987  6669  6699 W bt_btif_config: init unable to load config file: /data/misc/bluedroid/bt_config.conf; using backup.
01-18 11:52:21.987  6669  6699 E         : [0118/115221.987386:ERROR:config.cc(74)] config_new: unable to open file '/data/misc/bluedroid/bt_config.bak': No such file or directory
01-18 11:52:21.987  6669  6699 W bt_btif_config: init unable to load backup; attempting to transcode legacy file.
01-18 11:52:21.987  6669  6699 E bt_btif_config_transcode: btif_config_transcode unable to load XML file '/data/misc/bluedroid/bt_config.xml': 3
01-18 11:52:21.987  6669  6699 E bt_btif_config: init unable to transcode legacy file; creating empty config.
01-18 11:52:21.994  6669  6704 I bt_osi_thread: run_thread: thread id 6704, thread name alarm_default_ca started
01-18 11:52:21.994  6669  6705 I bt_osi_thread: run_thread: thread id 6705, thread name alarm_dispatcher started
01-18 11:52:21.996  6669  6699 I bt_btif_core: btif_init_bluetooth entered
01-18 11:52:21.997  6669  6699 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
01-18 11:52:22.000  6669  6706 I bt_osi_thread: run_thread: thread id 6706, thread name bt_jni_workqueue started
01-18 11:52:22.001  6669  6699 I bt_btif_core: btif_init_bluetooth finished
01-18 11:52:22.001  6669  6706 I bt_btif_core: run_message_loop entered
01-18 11:52:22.001  6669  6669 I bt_osi_wakelock: wakelock_set_os_callouts set to non-native
01-18 11:52:22.001  6669  6669 I bt_btif : get_profile_interface: id = socket
01-18 11:52:22.001  6669  6706 E bt_btif_storage: btif_storage_get_adapter_property: Controller not ready! Unable to return Bluetooth Address
01-18 11:52:22.002  6669  6706 E BluetoothServiceJni: adapter_properties_callback: Status 1 is incorrect
01-18 11:52:22.003  6669  6669 I bt_btif : get_profile_interface: id = sdp
01-18 11:52:22.009   552   552 D BluetoothManagerService: Bluetooth Adapter name changed to Xperia Z
01-18 11:52:22.009   552   552 D BluetoothManagerService: Stored Bluetooth name: Xperia Z
01-18 11:52:22.013  6669  6706 D AdapterProperties: Name is: Xperia Z
01-18 11:52:22.014  6669  6706 D AdapterProperties: BT Class:5a020c
01-18 11:52:22.016  6669  6669 I BluetoothAdapterService: Phone policy enabled
01-18 11:52:22.030  6669  6669 D BluetoothActiveDeviceManager: start()
01-18 11:52:22.031  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.047  6669  6669 D BluetoothAdapterService: setAdapterService() - trying to set service to com.android.bluetooth.btservice.AdapterService@3c47d13
01-18 11:52:22.048  6669  6709 D BluetoothActiveDeviceManager: onAudioDevicesAdded
01-18 11:52:22.048  6669  6709 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 1
01-18 11:52:22.048  6669  6709 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 2
01-18 11:52:22.048  6669  6709 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 15
01-18 11:52:22.048  6669  6709 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 15
01-18 11:52:22.048  6669  6709 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 18
01-18 11:52:22.048  6669  6709 D BluetoothActiveDeviceManager: Audio device added: Xperia Z type: 16
01-18 11:52:22.052  6669  6669 D BluetoothAdapterService: onBind()
01-18 11:52:22.053   552   552 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
01-18 11:52:22.053   552   592 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
01-18 11:52:22.054   552   592 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
01-18 11:52:22.063  6669  6686 D BluetoothAdapterService: enable() - Enable called with quiet mode status =  false
01-18 11:52:22.063  6669  6698 I AdapterState: BLE_TURNING_ON : entered 
01-18 11:52:22.063  6669  6698 D AdapterProperties: Setting state to BLE_TURNING_ON
01-18 11:52:22.063  6669  6698 D BluetoothAdapterService: updateAdapterState() - Broadcasting state BLE_TURNING_ON to 1 receivers.
01-18 11:52:22.064  6669  6698 D BluetoothAdapterService: bleOnProcessStart()
01-18 11:52:22.065  6669  6698 I AdapterProperties: init(), maxConnectedAudioDevices, default=5, propertyOverlayed=5, finalValue=5
01-18 11:52:22.068   552   592 D BluetoothManagerService: MESSAGE_GET_NAME_AND_ADDRESS
01-18 11:52:22.068  6669  6698 D BluetoothAdapterService: bleOnProcessStart() - Make Bond State Machine
01-18 11:52:22.069  6669  6698 D BluetoothBondStateMachine: make
01-18 11:52:22.070   552   592 D BluetoothManagerService: Stored Bluetooth name: Xperia Z
01-18 11:52:22.071   552   592 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: OFF > BLE_TURNING_ON
01-18 11:52:22.071   552   592 D BluetoothManagerService: Sending BLE State Change: OFF > BLE_TURNING_ON
01-18 11:52:22.081  6669  6712 I BluetoothBondStateMachine: StableState(): Entering Off State
01-18 11:52:22.086  6669  6669 I BtGatt.JNI: classInitNative(L875): classInitNative: Success!
01-18 11:52:22.087  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.131  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.151  6669  6669 D BtGatt.DebugUtils: handleDebugAction() action=null
01-18 11:52:22.153  6669  6669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c47d13
01-18 11:52:22.159  6669  6669 I bt_btif : get_profile_interface: id = gatt
01-18 11:52:22.160  6669  6669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c47d13
01-18 11:52:22.167  6669  6683 I droid.bluetoot: Background concurrent copying GC freed 103104(4MB) AllocSpace objects, 20(484KB) LOS objects, 63% free, 3MB/9MB, paused 183us total 288.696ms
01-18 11:52:22.181  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.183  6669  6669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c47d13
01-18 11:52:22.186  6669  6669 D BluetoothAdapterService: handleMessage() - Message: 2
01-18 11:52:22.186  6669  6669 D BluetoothAdapterService: handleMessage() - MESSAGE_PROFILE_SERVICE_REGISTERED
01-18 11:52:22.186  6669  6669 D BluetoothAdapterService: handleMessage() - Message: 1
01-18 11:52:22.186  6669  6669 D BluetoothAdapterService: handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
01-18 11:52:22.188  6669  6669 I bt_btif : enable: start restricted = 0
01-18 11:52:22.189  6669  6699 I bt_stack_manager: event_start_up_stack is bringing up the stack
01-18 11:52:22.190  6669  6699 I bt_core_module: module_start_up Starting module "btif_config_module"
01-18 11:52:22.191  6669  6699 I bt_core_module: module_start_up Started module "btif_config_module"
01-18 11:52:22.191  6669  6699 I bt_core_module: module_start_up Starting module "btsnoop_module"
01-18 11:52:22.191  6669  6699 I bt_core_module: module_start_up Started module "btsnoop_module"
01-18 11:52:22.191  6669  6699 I bt_core_module: module_start_up Starting module "hci_module"
01-18 11:52:22.191  6669  6699 I bt_hci  : hci_module_start_up
01-18 11:52:22.198  6669  6725 I bt_osi_thread: run_thread: thread id 6725, thread name hci_thread started
01-18 11:52:22.198  6669  6725 I bt_hci  : hci_initialize
01-18 11:52:22.199  6669  6699 D bt_hci  : hci_module_start_up starting async portion
01-18 11:52:22.200   213   213 W hwservicemanager: getTransport: Cannot find entry android.hardware.bluetooth@1.0::IBluetoothHci/default in either framework or device manifest.
01-18 11:52:22.203  6669  6725 D vndksupport: Loading /vendor/lib/hw/android.hardware.bluetooth@1.0-impl.so from current namespace instead of sphal namespace.
01-18 11:52:22.208  6669  6725 I bt_hci  : hci_initialize: IBluetoothHci::getService() returned 0xadb1ecc0 (local)
01-18 11:52:22.208  6669  6725 I android.hardware.bluetooth@1.0-impl: BluetoothHci::initialize()
01-18 11:52:22.209  6669  6725 D         : get_local_address: Trying /data/misc/bluetooth/bdaddr
01-18 11:52:22.210  6669  6725 D         : get_local_address: Got Factory BDA 00:eb:2d:0c:55:ea
01-18 11:52:22.210  6669  6725 I bt_vendor: ++init
01-18 11:52:22.210  6669  6725 I bt_vendor: bt-vendor : get_bt_soc_type
01-18 11:52:22.210  6669  6725 I bt_vendor: vendor.qcom.bluetooth.soc set to smd
01-18 11:52:22.210  6669  6725 I bt_vendor: vendor.qcom.bluetooth.soc not set, so using default.
01-18 11:52:22.210  6669  6725 I bt_vendor: BD Address: ea:55:0c:2d:eb:00
01-18 11:52:22.211  6669  6725 D android.hardware.bluetooth@1.0-impl: Open vendor library loaded
01-18 11:52:22.211  6669  6725 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
01-18 11:52:22.211  6669  6725 I bt_vendor: bluetooth status is on
01-18 11:52:22.211  6669  6725 I bt_vendor: bt-vendor : resetting BT status
01-18 11:52:22.211  6669  6725 W bt_vendor: Hw_config: nState = 0
01-18 11:52:22.211  6669  6725 W bt_vendor: Hw_config: nState = 1
01-18 11:52:22.211  6669  6725 I bt_vendor: bluetooth status is on
01-18 11:52:22.211  6669  6725 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
01-18 11:52:22.214  6669  6725 I bt_vendor: Done intiailizing UART
01-18 11:52:22.216  6669  6725 I bt_vendor: Done intiailizing UART
01-18 11:52:22.216  6669  6725 I bt_vendor: Bluetooth FW and transport layer are initialized
01-18 11:52:22.216  6669  6725 D android.hardware.bluetooth@1.0-impl: OnFirmwareConfigured result: 0
01-18 11:52:22.218  6669  6725 I android.hardware.bluetooth@1.0-impl: Firmware configured in 0.000s
01-18 11:52:22.218  6669  6725 I android.hardware.bluetooth@1.0-impl: OnFirmwareConfigured: lpm_timeout_ms 1000
01-18 11:52:22.218  6669  6725 I bt_vendor: __op: property_get: persist.vendor.service.bdroid.lpmcfg: all
01-18 11:52:22.218  6669  6725 D android.hardware.bluetooth@1.0-impl: low_power_mode_cb result: 0
01-18 11:52:22.218  6669  6725 D android.hardware.bluetooth@1.0-impl: OnFirmwareConfigured Calling StartLowPowerWatchdog()
01-18 11:52:22.218  6669  6725 I bt_hci  : event_finish_startup
01-18 11:52:22.218  6669  6699 I bt_core_module: module_start_up Started module "hci_module"
01-18 11:52:22.219  6669  6728 I bt_osi_thread: run_thread: thread id 6728, thread name bt_workqueue started
01-18 11:52:22.219  6669  6728 I         : [0118/115222.219685:INFO:btu_task.cc(107)] Bluetooth chip preload is complete
01-18 11:52:22.220  6669  6728 I         : [0118/115222.220540:INFO:gatt_api.cc(948)] GATT_Register 81818181-8181-8181-8181-818181818181
01-18 11:52:22.220  6669  6728 I         : [0118/115222.220692:INFO:gatt_api.cc(968)] allocated gatt_if=1
01-18 11:52:22.220  6669  6728 I         : [0118/115222.220814:INFO:gatt_api.cc(161)] GATTS_AddService
01-18 11:52:22.220  6669  6728 I         : [0118/115222.220906:INFO:gatt_api.cc(265)] GATTS_AddService: service parsed correctly, now starting
01-18 11:52:22.221  6669  6728 I         : [0118/115222.221211:INFO:gatt_api.cc(948)] GATT_Register 82828282-8282-8282-8282-828282828282
01-18 11:52:22.221  6669  6728 I         : [0118/115222.221303:INFO:gatt_api.cc(968)] allocated gatt_if=2
01-18 11:52:22.221  6669  6728 I         : [0118/115222.221394:INFO:gatt_api.cc(161)] GATTS_AddService
01-18 11:52:22.221  6669  6728 I         : [0118/115222.221486:INFO:gatt_api.cc(265)] GATTS_AddService: service parsed correctly, now starting
01-18 11:52:22.221  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_HCI : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_L2CAP : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_RFCOMM : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_AVDT : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_AVRC : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_A2D : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_BNEP : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_BTM : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_HID_HOST : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_PAN : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_SDP : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_SMP : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_HID_DEV : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_BTAPP : Level 2
01-18 11:52:22.222  6669  6728 I bt_bte  : BTE_InitTraceLevels -- TRC_BTIF : Level 2
01-18 11:52:22.222  6669  6729 I bt_osi_thread: run_thread: thread id 6729, thread name btu message loop started
01-18 11:52:22.227  6669  6730 I bt_osi_thread: run_thread: thread id 6730, thread name module_wrapper started
01-18 11:52:22.227  6669  6730 I bt_core_module: module_start_up Starting module "controller_module"
01-18 11:52:22.232  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.275  6669  6727 D bt_hci  : get_waiting_command VS event found treat it as valid 0xffff
01-18 11:52:22.275  6669  6730 E bt_hci  : read_command_complete_header: return status - 0x1
01-18 11:52:22.281  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.289  6669  6730 I bt_core_module: module_start_up Started module "controller_module"
01-18 11:52:22.289  6669  6730 W bt_osi_thread: run_thread: thread id 6730, thread name module_wrapper exited
01-18 11:52:22.290  6669  6728 W bt_btm  : btm_decode_ext_features_page: feature page 1 ignored
01-18 11:52:22.291  6669  6729 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0x5601cf5d
01-18 11:52:22.291  6669  6729 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0x5601cf5d 
01-18 11:52:22.291  6669  6729 I bt_stack: [INFO:gatt_api.cc(948)] GATT_Register 1578c5ae-2d61-d264-15c3-b4688f7cf2c4
01-18 11:52:22.291  6669  6729 I bt_stack: [INFO:gatt_api.cc(968)] allocated gatt_if=3
01-18 11:52:22.311  6669  6727 D bt_hci  : get_waiting_command VS event found treat it as valid 0xffff
01-18 11:52:22.311  6669  6729 F bt_stack: [FATAL:btm_ble_gap.cc(488)] Check failed: p_vcs_cplt_params->opcode == HCI_BLE_VENDOR_CAP_OCF. 
01-18 11:52:22.311  6669  6729 F libc    : Fatal signal 6 (SIGABRT), code -6 (SI_TKILL) in tid 6729 (btu message loo), pid 6669 (droid.bluetooth)
01-18 11:52:22.352  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.354   706   706 I ks      : type=1400 audit(0.0:476): avc: denied { read } for name="cmdline" dev="proc" ino=4026534188 scontext=u:r:kickstart:s0 tcontext=u:object_r:proc_cmdline:s0 tclass=file permissive=1
01-18 11:52:22.368   706   706 E kickstart: ERROR: function: sahara_start:340 IMEI reserved0 = 494d4549
01-18 11:52:22.354   706   706 I ks      : type=1400 audit(0.0:477): avc: denied { open } for name="cmdline" dev="proc" ino=4026534188 scontext=u:r:kickstart:s0 tcontext=u:object_r:proc_cmdline:s0 tclass=file permissive=1
01-18 11:52:22.354   706   706 I ks      : type=1400 audit(0.0:478): avc: denied { getattr } for path="/proc/cmdline" dev="proc" ino=4026534188 scontext=u:r:kickstart:s0 tcontext=u:object_r:proc_cmdline:s0 tclass=file permissive=1
01-18 11:52:22.368   706   706 E kickstart: ERROR: function: sahara_start:341 IMEI reserved1 = 35576205
01-18 11:52:22.368   706   706 E kickstart: ERROR: function: sahara_start:342 IMEI reserved2 = 44419080
01-18 11:52:22.377  6741  6741 W crash_dump32: failed to fetch registers for thread 6669: I/O error
01-18 11:52:22.381  6741  6741 W crash_dump32: failed to fetch registers for thread 6677: I/O error
01-18 11:52:22.381  6741  6741 W crash_dump32: failed to fetch registers for thread 6678: I/O error
01-18 11:52:22.381  6741  6741 W crash_dump32: failed to fetch registers for thread 6679: I/O error
01-18 11:52:22.383  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.386  6741  6741 W crash_dump32: failed to fetch registers for thread 6680: I/O error
01-18 11:52:22.387  6741  6741 W crash_dump32: failed to fetch registers for thread 6681: I/O error
01-18 11:52:22.387  6741  6741 W crash_dump32: failed to fetch registers for thread 6682: I/O error
01-18 11:52:22.387  6741  6741 W crash_dump32: failed to fetch registers for thread 6683: I/O error
01-18 11:52:22.387  6741  6741 W crash_dump32: failed to fetch registers for thread 6686: I/O error
01-18 11:52:22.388  6741  6741 W crash_dump32: failed to fetch registers for thread 6687: I/O error
01-18 11:52:22.388  6741  6741 W crash_dump32: failed to fetch registers for thread 6698: I/O error
01-18 11:52:22.388  6741  6741 W crash_dump32: failed to fetch registers for thread 6699: I/O error
01-18 11:52:22.389  6741  6741 W crash_dump32: failed to fetch registers for thread 6702: I/O error
01-18 11:52:22.389  6741  6741 W crash_dump32: failed to fetch registers for thread 6703: I/O error
01-18 11:52:22.389  6741  6741 W crash_dump32: failed to fetch registers for thread 6704: I/O error
01-18 11:52:22.389  6741  6741 W crash_dump32: failed to fetch registers for thread 6705: I/O error
01-18 11:52:22.391   706   706 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/m9kefs1' for writing
01-18 11:52:22.391  6741  6741 W crash_dump32: failed to fetch registers for thread 6706: I/O error
01-18 11:52:22.391  6741  6741 W crash_dump32: failed to fetch registers for thread 6709: I/O error
01-18 11:52:22.392  6741  6741 W crash_dump32: failed to fetch registers for thread 6710: I/O error
01-18 11:52:22.392  6741  6741 W crash_dump32: failed to fetch registers for thread 6711: I/O error
01-18 11:52:22.392  6741  6741 W crash_dump32: failed to fetch registers for thread 6712: I/O error
01-18 11:52:22.392  6741  6741 W crash_dump32: failed to fetch registers for thread 6720: I/O error
01-18 11:52:22.393  6741  6741 W crash_dump32: failed to fetch registers for thread 6721: I/O error
01-18 11:52:22.393  6741  6741 W crash_dump32: failed to fetch registers for thread 6724: I/O error
01-18 11:52:22.393  6741  6741 W crash_dump32: failed to fetch registers for thread 6725: I/O error
01-18 11:52:22.393  6741  6741 W crash_dump32: failed to fetch registers for thread 6727: I/O error
01-18 11:52:22.394  6741  6741 W crash_dump32: failed to fetch registers for thread 6728: I/O error
01-18 11:52:22.421  6741  6741 I crash_dump32: obtaining output fd from tombstoned, type: kDebuggerdTombstone
01-18 11:52:22.425   320   320 I /system/bin/tombstoned: received crash request for pid 6729
01-18 11:52:22.426  6741  6741 I crash_dump32: performing dump of process 6669 (target tid = 6729)
01-18 11:52:22.443  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.484  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.503   285   285 E WifiHAL : wifi_get_link_stats: requestResponse Error:-3
01-18 11:52:22.510   552   783 E WifiVendorHal: getWifiLinkLayerStats(l.937) failed {.code = ERROR_NOT_SUPPORTED, .description = }
01-18 11:52:22.511   706   706 I kickstart: STATUS: Received file 'm9kefs1'
01-18 11:52:22.511   706   706 I kickstart: STATUS: 786432 bytes transferred in 0.120240 seconds
01-18 11:52:22.511   706   706 I kickstart: STATUS: Successfully downloaded files from target 
01-18 11:52:22.520  6741  6741 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
01-18 11:52:22.521  6741  6741 F DEBUG   : crDroid Version: '5.0'
01-18 11:52:22.521  6741  6741 F DEBUG   : Build fingerprint: 'Sony/C6603/C6603:5.1.1/10.7.A.0.228/58103698:user/release-keys'
01-18 11:52:22.521  6741  6741 F DEBUG   : Revision: '0'
01-18 11:52:22.521  6741  6741 F DEBUG   : ABI: 'arm'
01-18 11:52:22.521  6741  6741 F DEBUG   : pid: 6669, tid: 6729, name: btu message loo  >>> com.android.bluetooth <<<
01-18 11:52:22.521  6741  6741 F DEBUG   : signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
01-18 11:52:22.521  6741  6741 F DEBUG   : Abort message: '[FATAL:btm_ble_gap.cc(488)] Check failed: p_vcs_cplt_params->opcode == HCI_BLE_VENDOR_CAP_OCF. 
01-18 11:52:22.521  6741  6741 F DEBUG   : '
01-18 11:52:22.521  6741  6741 F DEBUG   :     r0  00000000  r1  00001a49  r2  00000006  r3  00000008
01-18 11:52:22.521  6741  6741 F DEBUG   :     r4  00001a0d  r5  00001a49  r6  53ea996c  r7  0000010c
01-18 11:52:22.521  6741  6741 F DEBUG   :     r8  53ea99a4  r9  53ea9df4  r10 53ea9998  r11 53ea9df0
01-18 11:52:22.521  6741  6741 F DEBUG   :     ip  00000041  sp  53ea9958  lr  ae77404d  pc  ae76bdbe
01-18 11:52:22.527   706   706 I kickstart: STATUS: Sahara protocol completed
01-18 11:52:22.561  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:22.608  6741  6741 F DEBUG   : 
01-18 11:52:22.608  6741  6741 F DEBUG   : backtrace:
01-18 11:52:22.608  6741  6741 F DEBUG   :     #00 pc 0001cdbe  /system/lib/libc.so (abort+58)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #01 pc 0007b5d7  /system/lib/libchrome.so (base::debug::BreakDebugger()+10)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #02 pc 0008b2ff  /system/lib/libchrome.so (logging::LogMessage::~LogMessage()+746)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #03 pc 001464d7  /system/lib/libbluetooth.so (btm_ble_vendor_capability_vsc_cmpl_cback(tBTM_VSC_CMPL*)+78)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #04 pc 00150a5b  /system/lib/libbluetooth.so (btm_vsc_complete(unsigned char*, unsigned short, unsigned short, void (*)(tBTM_VSC_CMPL*))+38)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #05 pc 00160bd1  /system/lib/libbluetooth.so (btu_hcif_command_complete_evt_on_task(BT_HDR*, void*)+440)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #06 pc 0007c503  /system/lib/libchrome.so (base::debug::TaskAnnotator::RunTask(char const*, base::PendingTask*)+162)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #07 pc 0008e145  /system/lib/libchrome.so (base::MessageLoop::RunTask(base::PendingTask*)+324)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #08 pc 0008e37b  /system/lib/libchrome.so (base::MessageLoop::DeferOrRunPendingTask(base::PendingTask)+26)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #09 pc 0008e61f  /system/lib/libchrome.so (base::MessageLoop::DoWork()+218)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #10 pc 0008f313  /system/lib/libchrome.so (base::MessagePumpDefault::Run(base::MessagePump::Delegate*)+98)
01-18 11:52:22.608  6741  6741 F DEBUG   :     #11 pc 0008df2f  /system/lib/libchrome.so (base::MessageLoop::RunHandler()+62)
01-18 11:52:22.609  6741  6741 F DEBUG   :     #12 pc 000a1cad  /system/lib/libchrome.so (base::RunLoop::Run()+80)
01-18 11:52:22.609  6741  6741 F DEBUG   :     #13 pc 00161075  /system/lib/libbluetooth.so (btu_message_loop_run(void*)+188)
01-18 11:52:22.609  6741  6741 F DEBUG   :     #14 pc 001b17f1  /system/lib/libbluetooth.so (work_queue_read_cb(void*)+52)
01-18 11:52:22.609  6741  6741 F DEBUG   :     #15 pc 001b03ab  /system/lib/libbluetooth.so (run_reactor(reactor_t*, int)+218)
01-18 11:52:22.609  6741  6741 F DEBUG   :     #16 pc 001b02a5  /system/lib/libbluetooth.so (reactor_start(reactor_t*)+44)
01-18 11:52:22.609  6741  6741 F DEBUG   :     #17 pc 001b1443  /system/lib/libbluetooth.so (run_thread(void*)+142)
01-18 11:52:22.609  6741  6741 F DEBUG   :     #18 pc 00064a63  /system/lib/libc.so (__pthread_start(void*)+22)
01-18 11:52:22.609  6741  6741 F DEBUG   :     #19 pc 0001dfd5  /system/lib/libc.so (__start_thread+32)
01-18 11:52:22.631  1347  1374 I chatty  : uid=0(root) /system/bin/mpdecision identical 2 lines
01-18 11:52:22.685  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.225  1017  1017 I Choreographer: Skipped 31 frames!  The application may be doing too much work on its main thread.
01-18 11:52:23.232  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.286  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.288  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.368   320   320 E /system/bin/tombstoned: Tombstone written to: /data/tombstones/tombstone_45
01-18 11:52:23.383  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.384  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.416   552   590 I BootReceiver: Copying /data/tombstones/tombstone_45 to DropBox (SYSTEM_TOMBSTONE)
01-18 11:52:23.432  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.433  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.446   552   585 I ActivityManager: Showing crash dialog for package com.android.bluetooth u0
01-18 11:52:23.485  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.486  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.531  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.532  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.552   552   584 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.stats.service.DropBoxEntryAddedReceiver
01-18 11:52:23.552   552   584 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.chimera.GmsIntentOperationService$PersistentTrustedReceiver
01-18 11:52:23.583  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.584  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.627   552   585 W Looper  : Slow dispatch took 202ms android.ui h=com.android.server.am.ActivityManagerService$UiHandler c=null m=1
01-18 11:52:23.631  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.638  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.681  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.682  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.736  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.737  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.745   291   364 D SurfaceFlinger: duplicate layer name: changing Application Error: com.android.bluetooth to Application Error: com.android.bluetooth#3
01-18 11:52:23.757   552  2673 W Adreno-EGL: <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
01-18 11:52:23.772   552   585 W Looper  : Slow dispatch took 125ms android.ui h=android.view.Choreographer$FrameHandler c=android.view.Choreographer$FrameDisplayEventReceiver@54bdc73 m=0
01-18 11:52:23.781  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.782  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.784   552  2673 D vndksupport: Loading /vendor/lib/hw/gralloc.msm8960.so from current namespace instead of sphal namespace.
01-18 11:52:23.831  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.833  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.838   552   584 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.stats.service.DropBoxEntryAddedReceiver
01-18 11:52:23.838   552   584 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.chimera.GmsIntentOperationService$PersistentTrustedReceiver
01-18 11:52:23.882  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.883  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.921   552   552 D BluetoothManagerService: BluetoothServiceConnection, disconnected: com.android.bluetooth.btservice.AdapterService
01-18 11:52:23.922   552   592 E BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED(1)
01-18 11:52:23.922   552   592 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 7 receivers.
01-18 11:52:23.936  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.937  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.937   552   564 I ActivityManager: Process com.android.bluetooth (pid 6669) has died: psvc PER 
01-18 11:52:23.938   552   564 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.gatt.GattService in 1000ms
01-18 11:52:23.938   552   564 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
01-18 11:52:23.939   552   587 W libprocessgroup: kill(-6669, 9) failed: No such process
01-18 11:52:23.981  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:23.982  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:23.983   552   587 W libprocessgroup: kill(-6669, 9) failed: No such process
01-18 11:52:24.014   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_WAKELOCK_ACQUIRE
01-18 11:52:24.014   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_WAIT_READ
01-18 11:52:24.014   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_CLIENT_TX
01-18 11:52:24.014   296   720 D QC-QMI  : qmi_qmux: TX/RX - RX 19 bytes on conn_id=18
01-18 11:52:24.014   296   720 D QC-QMI  : qmuxd: TX message on fd=17, to qmux_client_id=0x0, len=53
01-18 11:52:24.014   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_WAKELOCK_RELEASE
01-18 11:52:24.014   296   720 D QC-QMI  : Thread state: conn_id=18, state=RX_THREAD_WAIT_POLL
01-18 11:52:24.014   316   731 D QC-QMI  : qmi_client [316] 0: Received 53 bytes on fd = 12
01-18 11:52:24.014   316   731 D QC-QMI  : qmi_service.c RX indication for conn=18, srvc=3
01-18 11:52:24.014   316   731 D QC-QMI  : Processing indication: Mesage4 ID=  81, Service ID = 3
01-18 11:52:24.014   316   731 D QC-QMI  : Client 12010300 gets indication callback
01-18 11:52:24.024   552   587 W libprocessgroup: kill(-6669, 9) failed: No such process
01-18 11:52:24.031  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.032  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.061   552   587 W libprocessgroup: kill(-6669, 9) failed: No such process
01-18 11:52:24.061   552   587 I libprocessgroup: Successfully killed process cgroup uid 1002 pid 6669 in 122ms
01-18 11:52:24.062   259   259 I Zygote  : Process 6669 exited due to signal (6)
01-18 11:52:24.081  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.082  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.127   552   592 D BluetoothManagerService: MESSAGE_RESTART_BLUETOOTH_SERVICE
01-18 11:52:24.133  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.134  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.181  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.183  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.231  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.233  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.283  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.285  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.331  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.333  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.381  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.383  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.431  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.434  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.483  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.484  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.504   552  2673 I OpenGLRenderer: Davey! duration=797ms; Flags=0, IntendedVsync=880273388744, Vsync=880373388746, OldestInputEvent=9223372036854775807, NewestInputEvent=0, HandleInputStart=880382832600, AnimationStart=880382863117, PerformTraversalsStart=880382893635, DrawStart=880612294269, SyncQueued=880614735675, SyncStart=880658955646, IssueDrawCommandsStart=880693837240, SwapBuffers=880908497882, FrameCompleted=881114766195, DequeueBufferDuration=67810000, QueueBufferDuration=32592000, 
01-18 11:52:24.505   552   585 W Looper  : Slow dispatch took 733ms android.ui h=android.view.Choreographer$FrameHandler c=android.view.Choreographer$FrameDisplayEventReceiver@54bdc73 m=0
01-18 11:52:24.519   552   585 W Looper  : Slow delivery took 813ms android.ui h=com.android.server.policy.PhoneWindowManager$PolicyHandler c=com.android.server.policy.PhoneWindowManager$29@727adf0 m=0
01-18 11:52:24.522   552   585 I Choreographer: Skipped 30 frames!  The application may be doing too much work on its main thread.
01-18 11:52:24.532  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.533  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.583  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.584  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.632  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.633  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.681  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.682  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.731  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.732  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.781  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.784  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.833  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.835  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.881  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.883  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.915   552  2673 I OpenGLRenderer: Davey! duration=908ms; Flags=0, IntendedVsync=880616822283, Vsync=881116822293, OldestInputEvent=9223372036854775807, NewestInputEvent=0, HandleInputStart=881132924153, AnimationStart=881132954670, PerformTraversalsStart=881132954670, DrawStart=881315907551, SyncQueued=881315907551, SyncStart=881315968586, IssueDrawCommandsStart=881316151691, SwapBuffers=881424092366, FrameCompleted=881525227620, DequeueBufferDuration=8422000, QueueBufferDuration=335000, 
01-18 11:52:24.906   278   278 I healthd : type=1400 audit(0.0:479): avc: denied { read } for name="present" dev="sysfs" ino=18017 scontext=u:r:healthd:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
01-18 11:52:24.906   278   278 I healthd : type=1400 audit(0.0:480): avc: denied { open } for name="present" dev="sysfs" ino=18017 scontext=u:r:healthd:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
01-18 11:52:24.922   552   585 W Looper  : Slow dispatch took 400ms android.ui h=android.view.Choreographer$FrameHandler c=android.view.Choreographer$FrameDisplayEventReceiver@54bdc73 m=0
01-18 11:52:24.931  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.932  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.982  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:24.984  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.031  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.032  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.081  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.082  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.132  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.133  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:24.906   278   278 I healthd : type=1400 audit(0.0:481): avc: denied { getattr } for path="/sys/devices/platform/msm_ssbi.0/pm8921-core/pm8921-charger/power_supply/battery/present" dev="sysfs" ino=18017 scontext=u:r:healthd:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
01-18 11:52:25.181  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.184  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.233  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.234  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.235   552   585 W Looper  : Drained
01-18 11:52:25.283  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.284  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.332  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.333  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.382  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.383  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.435  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.436  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.481  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.482  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.534  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.535  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.546   285   285 E WifiHAL : wifi_get_link_stats: requestResponse Error:-3
01-18 11:52:25.547   552   783 E WifiVendorHal: getWifiLinkLayerStats(l.937) failed {.code = ERROR_NOT_SUPPORTED, .description = }
01-18 11:52:25.581  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.582  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.631  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.633  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.684  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.685  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.732  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.733  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.783  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.784  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.833  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.834  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.884  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.885  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.931  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.933  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:25.984  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:25.986  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.036  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.037  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.081  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.082  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.131  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.132  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.181  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.182  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.231  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.232  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.283  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.284  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.331  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.333  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.384  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.385  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.433  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.434  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.482  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.483  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.534  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.536  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.581  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.584  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.592   259  6673 I zygote  : Background concurrent copying GC freed 128300(5MB) AllocSpace objects, 21(504KB) LOS objects, 66% free, 3MB/9MB, paused 732us total 2.209s
01-18 11:52:26.633  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.635  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.685  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.688  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
01-18 11:52:26.733  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu1
01-18 11:52:26.735  1347  1374 E MP-Decision: Error 1 setting online status to 1 forcpu2
