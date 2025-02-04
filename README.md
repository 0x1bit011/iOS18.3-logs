# iOS18.3-logs
I Upgraded from 17.6 to 18.3 for a ression
here's logs ( please do not use it against me)

```
23:45:06.692:  Firmware is unpacking
00:31:58.925:  Checking required files
00:31:58.930:  Run the flash program of iTunes
00:31:59.941: restore library built Aug 27 2024 at 10:14:00
00:32:00.122: This is here just to make sure we empty our found devices queue
00:32:00.173: (null)
00:32:00.223: Failed to subscribe for booted OS device notifications.
00:32:00.274: Mux version 3 event happened
00:32:00.325: IPv6 @ locationID=0x26400000, NCM 0x10000091e: found remote address [fe80::98f5:bfff:feff:2a0%en3]
00:32:00.376: sock   8: connected to  [usbmux_2]:62078
00:32:00.427: connected to service com.apple.mobile.lockdown
00:32:00.479: using protocol version 0
00:32:00.532: supports value queries: 0
00:32:00.617: sock   8: closed
00:32:00.670: Successfully registered new client
00:32:00.787:  Registered device change listening service succeeded
00:32:00.787:  Searching iDevice, if not connected, please plug in the device again
00:32:00.837: Now tracking 1 clients
00:32:00.891: (null)
00:32:00.941: Muxed mode device connected with ECID: 0x1534A90C85802E
00:32:00.993: Found new device
00:32:01.044: Found a device with a known device registration class: 0x1
00:32:01.095: iTunesVersion: 'iTunes 12.9.5.5'
00:32:01.153: Created state machine for device with ECID=0x1534A90C85802E
00:32:01.237: State Machine Dump, status:RUNNING - [state:BootedOS remaining-cycles:1 (current state)] -> [state:Recovery remaining-
                     cycles:2] -> [state:RestoreOS remaining-cycles:1]
00:32:01.326: Found RSD device which supports lockdown, ignoring
00:32:01.378: AMRestorableDeviceCopyPSDProbe: Failure to locate probe for [0x26400000] in IORegistry
00:32:01.429: Could not find parent entry!
00:32:01.491: Could not get builtin port for service 39687
00:32:01.543: Successfully applied power assertion
00:32:01.594: requested restore behavior: Erase
00:32:01.594:  Flash mode: Don't Retain User's Data While Flashing
00:32:01.645: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: searching for variant Erase (0 recovery)
00:32:01.695: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: No baseband chipid reported. Will match Build Identity based on ap c
                     hipid, boardid, and secdomain only.
00:32:01.746: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: AMAuthInstallBundleCopyBuildIdentityForVariant: Found variant: Cust
                     omer Erase Install (IPSW)
00:32:01.797: Automatically set FormatForAPFS => True and FormatForLwVM => False.
00:32:01.862: Failed to create recovery OS variant , no recovery variant in options nor restore variant.
00:32:01.916: requested restore behavior: Erase
00:32:01.916:  Flash mode: Don't Retain User's Data While Flashing
00:32:01.966: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: variant not specified, will use first variant found for this device in bui
                     ld manifest
00:32:02.017: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: No baseband chipid reported. Will match Build Identity based on ap c
                     hipid, boardid, and secdomain only.
00:32:02.068: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: AMAuthInstallBundleCopyBuildIdentityForVariant: Found variant: Cus
                     tomer Erase Install (IPSW)
00:32:02.119: Couldn't find recovery OS variant in the restore variant based on the behavior based variant.
00:32:02.170: No recovery variant found in bundle, continue without recovery OS installation.
00:32:02.221: Not setting apfs boot-args because option is not set to true.
00:32:02.272: Changing state from '(null)' to 'Restoring'
00:32:02.272:  Starting flashing
00:32:02.323: Performing preflight on booted OS device...
00:32:02.386: Found AuthInstallRestoreBehavior and selecting behavior based on that.
00:32:02.437: Requesting system token be cleared.
00:32:02.488: Connected to PreboardService v2
00:32:02.539: Clearing system token succeeded.
00:32:02.633: Updater preflight query returned 4 entries.
00:32:02.685: Passing in 0 items to AMAuthInstallApSetParameters.
00:32:02.735: amai: AMAuthInstallSsoInitialize: can't find SSOClient.framework
00:32:02.786: requested restore behavior: Erase
00:32:02.786:  Flash mode: Don't Retain User's Data While Flashing
00:32:02.836: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: searching for variant Erase (0 recovery)
00:32:02.901: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: AMAuthInstallBundleCopyBuildIdentityForVariant: Found variant: Cust
                     omer Erase Install (IPSW)
00:32:02.951: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:32:03.003: no override trust object found
00:32:03.054: requested restore behavior: Erase
00:32:03.054:  Flash mode: Don't Retain User's Data While Flashing
00:32:03.106: amai: AMAuthInstallBasebandSetParametersWithUpdaterOutput: baseband updater output: {
00:32:03.165:     CertID = 524245983;
00:32:03.217:     ChipID = 104;
00:32:03.268: 00:32:03.318: 00:32:03.369: 00:32:03.420:     EUICCChipID = 5;
00:32:03.471: 00:32:03.523: 00:32:03.574: 00:32:03.625:     EUICCTicketVersion = 0;
00:32:03.676:     FusingStatus = 3;
00:32:03.727: 00:32:03.778: 00:32:03.829:     SKeyStatus = 2;
00:32:03.880:     VendorID = 2;
00:32:03.933: }
00:32:03.987: amai: AMAuthInstallBasebandSetParametersWithUpdaterOutput: manifest dict not found
00:32:04.038: amai: _AMAuthInstallBasebandCheckForParameterChange: goldCertID changed
00:32:04.089: amai: _AMAuthInstallBasebandCheckForParameterChange: nonce changed
00:32:04.140: amai: _AMAuthInstallBasebandCheckForParameterChange: eUICC Param 0 changed
00:32:04.191: amai: _AMAuthInstallBasebandCheckForParameterChange: eUICC Param 1 changed
00:32:04.242: amai: _AMAuthInstallBasebandCheckForParameterChange: eUICC Param 2 changed
00:32:04.293: amai: AMAuthInstallBasebandSetParametersWithUpdaterOutput: bbParameters changed, triggering bbfw re-personalization
00:32:04.343: Skipping preflight for Savage.
00:32:04.395: Skipping preflight for Rose.
00:32:04.446: Skipping preflight for SE.
00:32:04.496: Skipping preflight for T200.
00:32:04.548: requested restore behavior: Erase
00:32:04.548:  Flash mode: Don't Retain User's Data While Flashing
00:32:04.599: requested variant: Erase
00:32:04.650: no override trust object found
00:32:04.707: requested restore behavior: Erase
00:32:04.707:  Flash mode: Don't Retain User's Data While Flashing
00:32:04.757: requested restore behavior: Erase
00:32:04.758:  Flash mode: Don't Retain User's Data While Flashing
00:32:04.816: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:32:04.867: personalizing: <AMAuthInstall 0x7f9603c471a0>{ap=(personalize=YES d421ap ecid=0x1534a90c85802e, chipid=0x8030, boa
                     rdid=0x6, secDom=1, isProduction=YES, EPRO=YES, isSecure=YES, ESEC=YES, img4=YES, demotionPolicy=, managedBaa
                     Cert=NO, slowRollBaaCert=NO, dpoc=(null), nonce=0x9a4bb56d86043a5547611e7306861fa1aa056411a7fb17d1875a3c3be80
                     7baed, sepNonce=0xb307501e6e3952e15e1ba57d57f4d9405b85b12c), bp=(personalize=YES, snum=0x1258e37c46f782f200
                     000000, chipid=0x68, certid=0x1f3f5bdf, nonce=0x9380a7826a99e2107212bcfba00e1a6fb6c02ed4), UserAuth=NO, iTunes=
                     YES, server="https://gs.apple.com:443", locale=Zh_cn, version="libauthinstall-1033.0.6", platform=mac/19H15/x86_64}
00:32:04.959: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:32:05.009: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:32:05.060: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreLogo to Manifest to personalize later
00:32:05.111: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreDeviceTree to Manifest to personalize later
00:32:05.161: amai: AMAuthInstallApImg4FindProperty: failed to find property tag 0xe00000006d6d6170
00:32:05.213: amai: AMAuthInstallApImg4FindProperty: failed to find property tag 0xe000000072646467
00:32:05.264: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreKernelCache to Manifest to personalize later
00:32:05.315: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreRamDisk to Manifest to personalize later
00:32:05.367: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBEC to Manifest to personalize later
00:32:05.419: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBSS to Manifest to personalize later
00:32:05.470: amai: AMAuthInstallApImg4FindProperty: failed to find property tag 0xe00000006d6d6170
00:32:05.522: amai: AMAuthInstallApImg4FindProperty: failed to find property tag 0xe000000072646467
00:32:05.572: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting KernelCache to Manifest to personalize later
00:32:05.622: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftap to Manifest to personalize later
00:32:05.674: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfta to Manifest to personalize later
00:32:05.724: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftsp to Manifest to personalize later
00:32:05.779: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfts to Manifest to personalize later
00:32:05.834: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,SystemVolumeCanonicalMetadata to Manifest to person
                     alize later
00:32:05.926: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SystemVolume to Manifest to personalize later
00:32:05.977: amai: AMAuthInstallBasebandCreateMeasurements: Using set ChipID 0x00000068 to measure
00:32:05.977:  Requesting baseband SHSH via network
00:32:06.027: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA384 to hash PSI-Version
00:32:06.078: amai: AMAuthInstallRembrandtMeasureBootPSI: PSI-Version: version=0x98b1392
00:32:06.129: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA384 to hash RestorePSI-Version
00:32:06.179: amai: AMAuthInstallRembrandtMeasureBootPSI: RestorePSI-Version: version=0x98b1393
00:32:06.231: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA256 to hash PSI-Version
00:32:06.291: amai: AMAuthInstallRembrandtMeasureBootPSI: PSI-Version: version=0x98b1392
00:32:06.342: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA256 to hash RestorePSI-Version
00:32:06.394: amai: AMAuthInstallRembrandtMeasureBootPSI: RestorePSI-Version: version=0x98b1393
00:32:06.445: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 776 bytes]
00:32:06.495: amai: : 30 00 00 00 10 00 00 00 04 59 43 5a a7 dc 49 30
00:32:06.546: amai: : 0c 62 66 c5 0f c5 ed fa cf f0 18 08 c5 64 02 88
00:32:06.598: amai: : 58 b5 26 c6 6d 97 1a 77 00 09 76 29 3b 16 25 2f
00:32:06.656: amai: : bd 94 96 8c 0c b9 b7 f9 bf 9e 36 9e bc 1f 6b 2c
00:32:06.708: amai: : 0a 1d 9f 31 0b bf 3b b5 11 18 e5 7d ff f6 74 3c
00:32:06.758: amai: : 54 3b 53 0d ae 19 e3 6b 0a 68 da 9c d9 c0 43 f0
00:32:06.810: amai: : 1d 55 62 e4 0e 85 10 d8 82 cf f4 88 29 a6 c0 19
00:32:06.860: amai: : a4 78 d9 7c 3c 39 5f 9b 2d 34 93 c2 57 50 a9 25
00:32:06.911: amai: : ee eb 83 15 9a 25 07 52 6e 29 11 7c 93 6c e8 e6
00:32:06.961: amai: : fa 86 1e b3 8d 43 02 8f 81 26 11 37 d8 fc 28 54
00:32:07.012: amai: : 2d 9e 5e 5f b4 6e c8 50 9c b3 76 02 a9 ff 42 d7
00:32:07.063: amai: : 4b e9 b3 d5 b4 23 b2 ef 76 f2 b2 bc 00 d4 62 00
00:32:07.114: amai: : 80 11 19 c8 9b 0e 38 85 9d c1 07 44 28 1d 5b b2
00:32:07.165: amai: : 22 8f 01 61 a1 c2 72 50 4f 2e e6 d0 9a 09 a9 f8
00:32:07.216: amai: : d8 31 14 95 55 9f b0 44 cd 9f 30 f7 50 a8 6b 6a
00:32:07.267: amai: : 43 95 b4 1d 11 85 a9 12 52 99 dd e6 b2 b4 9b d2
00:32:07.317: amai: : d6 f3 2a 5b 13 38 f0 51 f8 6d 48 d0 23 12 80 c7
00:32:07.369: amai: : 08 aa ea ae 79 0d 2f 44 34 bd 1e 02 9b 19 f6 31
00:32:07.420: amai: : bb fa 2e 87 1c 04 ce c9 0e 47 3a f1 05 10 ad 5d
00:32:07.471: amai: : 2d 05 60 01 89 cc 98 d0 fc df 69 59 e5 eb 0f f8
00:32:07.523: amai: : 49 5f a8 f4 7b f8 83 8c 64 d0 58 82 16 93 ba 50
00:32:07.573: amai: : f1 dc 7a 15 2e 98 00 8d 60 22 1f 54 a7 7a b2 a9
00:32:07.629: amai: : b1 51 d4 4b f7 a3 5c 40 47 24 e3 79 32 0b 47 53
00:32:07.681: amai: : c1 c3 aa 70 5a b4 d6 f7 f2 a6 31 a9 63 d1 a1 96
00:32:07.751: amai: : 6a 16 a6 6b 08 2a 8b 18 61 81 43 d1 a3 90 d2 33
00:32:07.801: amai: : 64 49 cb 89 f2 65 fc b3 93 2f 87 5b 1b 0a 86 da
00:32:07.853: amai: : da dc 4b df 0a bc e6 55 81 04 a9 d5 39 49 3f 43
00:32:07.904: amai: : d9 1f 4c 09 82 62 21 b3 0a bc fc 44 d7 a7 85 fc
00:32:07.955: amai: : 96 9c 8b 19 d5 62 8d 38 2e 0d 93 c0 bb f5 98 c7
00:32:08.006: amai: : f5 f9 55 23 07 21 ab dc 85 3d 18 8c 04 35 1a aa
00:32:08.058: amai: : 2e 41 1f cb b4 97 81 43 b4 2f 79 d8 d9 f6 c3 87
00:32:08.109: amai: : 7b 4c 9d 95 83 ef da 24 0d f6 dd e8 95 44 aa 39
00:32:08.159: amai: : 0d 79 c5 19 60 06 97 cc 8c 4d 8f 67 20 fa c4 87
00:32:08.211: amai: : 2f f8 b5 46 9b 0a 1b 4c 9c a3 91 d6 17 30 f4 a0
00:32:08.262: amai: : 0b 0e 72 43 95 df a7 0c 78 c5 9a 1b c9 85 db 5b
00:32:08.313: amai: : 49 56 59 bd 87 e3 12 44 82 06 e7 26 7a dd 41 14
00:32:08.368: amai: : 3e 37 89 ab 65 1d ee 0d 5b 22 6a 86 54 b1 96 18
00:32:08.419: amai: : 4e 7a b5 58 86 dd a3 8d 7b e5 6c 3b ce ed 17 d1
00:32:08.470: amai: : c6 96 95 1c ef 1c 5f 5b 03 15 13 75 39 03 1c 39
00:32:08.521: amai: : 12 d6 e9 e0 66 76 6e f9 35 c6 ee 74 9d a4 9d 69
00:32:08.572: amai: : 70 cd 16 6d 95 74 1d 64 bc fd 5c 65 91 a6 f0 ca
00:32:08.622: amai: : fa bb 9c c0 3a 07 a2 35 9a c2 69 75 a2 04 dd 01
00:32:08.673: amai: : 2f f2 23 ca 32 2b 66 1a f9 e3 5a 10 85 ef 64 5f
00:32:08.725: amai: : 8a d1 8e 07 2e 92 cc 7f ca a7 b4 03 b9 cc 46 9a
00:32:08.775: amai: : ae 39 92 f8 b4 64 2f d5 4c 0a 77 2e fa 98 c3 b3
00:32:08.826: amai: : d8 5c b7 aa 52 1a 3a ff d8 ba 3a a3 8b 70 2f e9
00:32:08.877: amai: : ab 55 44 39 a0 9b 7d 8d c7 c2 03 f3 b5 7a de 9c
00:32:08.929: amai: : be ec b3 ea f0 9b ac 65 58 81 1d 19 ff f8 96 1e
00:32:08.980: amai: : 35 71 6d 0f 04 f7 65 c3
00:32:09.030: amai: : -----------------------------------------------
00:32:09.082: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 1976 bytes]
00:32:09.133: amai: : 30 00 00 00 29 00 00 00 63 15 1e cc c4 41 0e fb
00:32:09.184: amai: : 28 ab 8b 25 cd bc e8 f1 ec 60 e4 8d 2a fa bc a7
00:32:09.247: amai: : cd b4 e4 c2 e1 95 be 16 e2 1b b5 db db 4d fd 27
00:32:09.302: amai: : 7e ba d0 ad 4c 98 54 10 0b 61 31 d6 d6 bd 8d 46
00:32:09.352: amai: : 71 c5 eb 40 d3 f3 3f 92 7d 15 a0 a7 f2 f1 28 57
00:32:09.402: amai: : 1e 0a 16 27 aa dc d9 67 24 f0 ed ba 57 de 1e a0
00:32:09.454: amai: : 61 a2 e8 4a fa a0 92 6e 31 7a 72 d5 df 0a fc 2c
00:32:09.504: amai: : ff 5e 12 05 d2 4c 00 f5 1b c8 ac a5 1f a7 90 fd
00:32:09.555: amai: : 1d ee e4 9e 34 d0 9b 21 f4 f8 ff 74 89 bd f8 fc
00:32:09.606: amai: : 74 cf 62 19 79 da 63 e9 87 90 a2 84 6d 67 bf 9b
00:32:09.658: amai: : 59 4d ac f7 2f 65 bb 3a 5a 08 8c b9 12 47 09 03
00:32:09.715: amai: : 50 14 4a 98 dd 73 a9 f6 d8 ea 00 46 36 7d 14 58
00:32:09.766: amai: : c2 d9 8e 73 af f1 80 aa 55 70 64 89 91 c5 fe c2
00:32:09.818: amai: : 84 8c 86 1b 55 5e b4 e4 23 7e db f1 32 34 a8 c0
00:32:09.875: amai: : d0 fb 1f 96 e3 44 94 27 75 45 4d c1 fb 06 41 b2
00:32:09.927: amai: : 9e a6 05 dc da f8 c2 cd ec f9 b2 b3 34 63 41 8d
00:32:09.978: amai: : 15 e3 b9 39 6b a4 38 ed 60 47 ff 42 72 ac 86 fb
00:32:10.028: amai: : 45 70 60 53 ab e4 09 c6 7c 4f 64 ad 22 d9 8d 95
00:32:10.083: amai: : f3 4a 42 bf 0b 70 4d b5 0d 53 f2 4f 63 f0 dd 6f
00:32:10.135: amai: : 24 90 09 f2 63 0e 57 da 83 7d eb e1 88 4f 42 75
00:32:10.186: amai: : 68 ea 39 5b 3b 1d d7 64 a0 4d 8a 02 35 39 d4 2c
00:32:10.237: amai: : 2b 7c 45 9b 1f b7 47 6b 02 87 e0 70 12 31 61 58
00:32:10.288: amai: : 51 9d 66 74 24 b5 48 f0 3b ee 83 81 10 d3 e8 04
00:32:10.339: amai: : 03 69 f0 39 e4 53 87 f9 a1 1c 0f b8 4d 9f 93 9d
00:32:10.390: amai: : 3b 36 fe b1 27 44 7b 9e 5d 0f 67 a4 97 86 cc 5c
00:32:10.441: amai: : 46 72 e8 34 0e 3f 14 a1 f8 f4 bb 63 d4 ca 6e 32
00:32:10.492: amai: : 85 5e 34 81 bf 8c 20 ca 2c 40 6d 15 81 1f b3 1c
00:32:10.543: amai: : b8 4e 86 45 2b 1e 00 a5 0e 2c 86 51 0f f3 bb ba
00:32:10.594: amai: : 28 10 be f2 00 e8 31 29 0a e2 9f b9 60 42 6f e1
00:32:10.654: amai: : 34 bb 5e e7 29 c6 35 25 ef c7 76 b4 ae 8e ec f6
00:32:10.704: amai: : c5 f1 41 a3 6e 8c 04 66 ae 34 d0 ba 56 fc 5f 9c
00:32:10.756: amai: : fc 48 1a b0 27 cf e4 6b f8 a1 51 cf 14 ae 6f 04
00:32:10.808: amai: : ee c8 8e 3c 74 d8 f5 2c 4e 8f 7d bc cc eb f3 5a
00:32:10.884: amai: : 8a c0 20 2f 7d 8a 61 d0 b3 c4 96 ba 87 ae d8 a0
00:32:10.942: amai: : 5a fc 0c 89 15 42 8c d8 4f 24 6f 5b e2 33 84 75
00:32:11.045: amai: : 42 bd 3d 82 e8 ad b1 28 29 d1 80 96 4c 8b 98 6c
00:32:11.096: amai: : d1 7f 1b 98 28 70 b0 05 7f 33 a1 81 c4 be 25 3e
00:32:11.147: amai: : e4 0c e9 e7 84 27 af 94 1b a7 14 32 23 4e 7b 60
00:32:11.198: amai: : 36 59 8e 62 4e 50 07 80 5b ec d6 3a 5c 95 92 4a
00:32:11.249: amai: : 6b 5b 09 be be 0b da 69 96 64 b9 48 c8 cf 9c 28
00:32:11.300: amai: : be fe 06 2e 6c a1 92 f5 1a d1 8d 67 30 66 2e ac
00:32:11.351: amai: : 6b 6b b5 a8 73 04 15 54 34 f1 81 2b 6e b1 c4 0d
00:32:11.403: amai: : 53 3b 7f 51 ed 2f 04 76 ee 52 5a 5c fc 6d 4a 11
00:32:11.453: amai: : e0 8c dc 20 99 6f fc ff 3e df 68 4e fc 90 f3 6b
00:32:11.510: amai: : 76 88 5d c1 b3 db 17 ca db 9a a1 9a 28 d2 e7 e4
00:32:11.561: amai: : fd 4b 36 7d 18 d7 49 5d d1 9d c2 12 1e 65 74 93
00:32:11.612: amai: : ca 8b 23 c6 12 6b a4 20 62 92 b3 4e 4a 93 62 fd
00:32:11.664: amai: : 9b ea 26 a4 e7 89 7b 4b b5 66 7f 23 d8 a5 59 1d
00:32:11.715: amai: : be 45 01 40 26 5b 2f f2 bb 63 97 ba c6 96 ef 44
00:32:11.766: amai: : 9c ea 1f d0 d3 ef 1b 68 f2 5d 2a 58 6f e5 d5 c3
00:32:11.821: amai: : 28 c3 eb 48 ce 83 75 1e b5 1d dd 6f cc 5f 6b 95
00:32:11.872: amai: : 06 b4 90 25 84 f0 38 65 5d 6b 29 2e be ae b2 41
00:32:11.924: amai: : 7c be 65 31 ba eb a3 d2 c2 4b 57 a5 1c 4c a2 bd
00:32:11.975: amai: : 4d 59 83 be db 3e 31 be 7f a8 e0 63 a5 b0 7e 8d
00:32:12.025: amai: : 5b 58 8b 7f 5b 3c 43 0a 15 d3 d5 7b 6e 4c 82 d5
00:32:12.077: amai: : bb 05 42 45 7f 0b a5 d8 78 d2 e5 a8 71 19 b7 03
00:32:12.128: amai: : d5 f5 b4 f9 a5 27 f3 21 7b ff eb 12 25 ae 92 e8
00:32:12.179: amai: : dd b2 e2 89 cb 06 99 03 40 35 29 e2 91 5a 39 66
00:32:12.230: amai: : 9a a1 6c 1b 35 92 6b 34 30 39 9d d5 b5 29 a9 ca
00:32:12.280: amai: : e8 b7 a6 a6 84 f9 18 5c 69 ca 2f 11 d1 37 ed 49
00:32:12.332: amai: : e8 7f cc a4 c8 51 72 a8 45 63 ab 86 1f ed 36 e6
00:32:12.383: amai: : 99 76 dd 4c 49 ce c1 32 8d be 31 dd 19 da b5 4c
00:32:12.434: amai: : 55 87 df 27 a0 4f bb e0 47 15 d6 6a 72 8d 4e 6e
00:32:12.486: amai: : cb f3 a7 1d 63 c6 90 5c 80 04 6c 64 53 6c a6 7a
00:32:12.544: amai: : 15 81 fc ae 62 83 76 e0 bb 5d 02 d1 36 82 d0 6f
00:32:12.595: amai: : 2b a6 03 4b 20 33 81 f3 72 7c 8d b7 8b 1c da 46
00:32:12.646: amai: : d9 8d ff f9 48 6a fb a3 29 98 31 18 00 f2 2a d2
00:32:12.700: amai: : 7e bc 89 cc da c9 2d 87 2d 03 d2 11 15 e7 be 00
00:32:12.758: amai: : 86 7c ce 00 49 5b 8a 01 f9 bb dc 41 22 d5 29 e4
00:32:12.809: amai: : 09 69 15 be 06 6d 12 6d ed 2e b5 46 50 1d 6f 37
00:32:12.860: amai: : bc c6 8a c8 70 b9 a8 66 c3 e2 c1 6d da 75 22 4a
00:32:12.911: amai: : 68 43 58 f9 8d 00 a8 4d 15 98 a1 e2 7b 95 86 f7
00:32:12.962: amai: : 3b 45 7c 3d 12 a4 be 97 08 c3 ab 86 18 ad 61 20
00:32:13.019: amai: : c0 27 bc 7e 10 bc 6b 0e 8a 08 5c 5f 19 35 4c 89
00:32:13.070: amai: : 03 02 1e f3 cb 4b 0c 51 49 ef f9 ca cf 24 55 8d
00:32:13.122: amai: : 10 52 ee c2 bf b1 53 28 50 c0 fd 97 e3 8f cc f1
00:32:13.173: amai: : f1 0e f3 fc 84 ae d6 3e a7 40 e6 9c fe 7e c5 17
00:32:13.231: amai: : a3 5b ba 54 0a e5 14 09 9e 0a 45 dc b5 fb 2f 37
00:32:13.284: amai: : af 05 0e 16 08 4e c8 d8 c9 35 2d 32 f6 8f 31 03
00:32:13.335: amai: : ca e4 9b e9 0b bd 95 8a 4e d5 bb 57 a6 ec f7 6b
00:32:13.397: amai: : e4 ce b8 26 35 f7 2b 98 dd 86 8d 7e 05 5e d8 74
00:32:13.447: amai: : 43 49 12 a0 c4 98 7a c1 6f 6d b9 72 b2 88 b0 e4
00:32:13.499: amai: : 96 73 8c b1 65 28 88 ad ed 36 72 7c 44 d0 5f 20
00:32:13.551: amai: : 46 6e 73 7a fb 3e 1a 1d a6 57 f1 46 ae ff 1a 09
00:32:13.610: amai: : ce ab b9 7a 98 17 61 08 7b f0 51 c5 03 f9 eb 0e
00:32:13.661: amai: : a3 31 89 b7 4e 2f b1 8e ec 96 7a 48 eb f9 91 a5
00:32:13.716: amai: : 26 ba 7e 66 86 ff 6b 6c e6 59 40 1d 0b e3 0d 14
00:32:13.776: amai: : 90 86 9f 8d a7 e4 fe 91 53 73 b5 00 91 8f 59 54
00:32:13.827: amai: : 56 e4 d2 0c 08 5f 0b 7b 4b 56 82 ea a6 f4 ef e9
00:32:13.883: amai: : 4c 7e e0 42 4b e6 05 80 a7 11 a2 ed 96 09 3a 38
00:32:13.934: amai: : 4c c4 a8 0d 29 9e fa 38 26 9a 8a c0 06 47 24 ee
00:32:13.988: amai: : 50 c4 c5 3d ff c5 34 89 dc df 55 65 f2 cd f7 e9
00:32:14.046: amai: : ff d3 6e 76 96 a9 33 96 14 12 58 6b d9 5d 8e 2d
00:32:14.099: amai: : 85 ba a6 6e 56 0f 38 b4 ba 3d 3d 77 eb 69 2e 34
00:32:14.152: amai: : e1 30 23 86 90 fb 83 2f d2 64 6c 99 17 4a 8b b7
00:32:14.204: amai: : fc 39 71 f0 26 0d 6a b0 53 7c 52 2d d0 e6 83 ac
00:32:14.254: amai: : eb 42 e3 79 6b 7a ea 9d 1b 75 f8 6e 31 80 41 08
00:32:14.306: amai: : c9 be d4 aa 86 4d 4c ad 97 b9 37 80 f0 fd dd 91
00:32:14.357: amai: : 6e 46 b8 8e 93 b0 8a ec aa 54 b9 94 04 ab b0 6c
00:32:14.408: amai: : d4 71 0f 82 c4 e4 7d 19 c1 73 44 08 fa 8f 7d 0e
00:32:14.460: amai: : 08 08 2f 6a 6c 58 41 68 a9 df af c8 88 9b 10 7f
00:32:14.510: amai: : 33 7f d6 28 28 c8 79 7f a2 c8 40 13 c3 78 e5 a4
00:32:14.561: amai: : 20 75 7b 33 f8 a3 53 e1 19 93 4a 01 45 56 68 09
00:32:14.612: amai: : 1e 62 8e 7c f4 ee 9a 8d 99 ed 83 91 84 d3 77 d4
00:32:14.663: amai: : ed 05 a4 2b 81 d0 8b 96 98 b8 14 4f db a9 12 ed
00:32:14.715: amai: : 95 45 c0 06 f0 53 59 49 15 43 c2 6f 54 86 7a 2a
00:32:14.766: amai: : 9e 3c 1a 4c 34 46 70 97 19 8b fd 40 ca fe 5c fb
00:32:14.818: amai: : 7b 28 ea 3b 20 09 a2 50 3d 2f d0 5b ff 57 94 17
00:32:14.869: amai: : 5f 59 fa 35 52 ab 6d 3d e3 06 ba 06 38 d5 a0 7c
00:32:14.920: amai: : 80 18 d7 d6 ab 47 80 77 16 97 7d 50 3e 68 48 26
00:32:14.971: amai: : 2e 14 9c 16 43 ed fc 85 6f a3 11 78 29 b5 59 d8
00:32:15.022: amai: : bb e9 80 9d 26 5c 17 34 47 d0 c6 e7 d5 33 f2 5c
00:32:15.073: amai: : 15 4d 53 c7 91 39 c4 46 a7 26 b1 d5 7d 64 86 ee
00:32:15.124: amai: : 97 06 79 f4 03 f7 a6 66 26 b7 7a 34 ba 6d b0 54
00:32:15.176: amai: : da be b2 57 2c d2 96 fa 5a 22 1c 87 36 eb 29 4f
00:32:15.233: amai: : 1e 6e 87 27 b8 39 1a d3 e0 1f 20 f3 3e 41 13 21
00:32:15.285: amai: : 66 9c b3 ea 79 dd 36 e5 9e 15 aa 41 a7 c5 7d cb
00:32:15.336: amai: : 19 7e b6 57 0e 2a d7 e6 52 76 bd e9 1f 19 a5 f9
00:32:15.387: amai: : 27 90 76 45 7c 9a 96 0c d3 02 cc e2 de 6e 62 ff
00:32:15.438: amai: : 49 99 b6 1a a1 be 71 6c 3b 10 c4 12 dd 30 8a ab
00:32:15.489: amai: : 55 57 79 21 e7 c0 e3 80 75 47 0a eb 8e 14 b6 d4
00:32:15.540: amai: : 6f e1 7a 7e 5e 3e 8e 70 e8 8d fc 98 89 15 d9 0b
00:32:15.591: amai: : 79 7c 6f 49 99 df 72 d8 72 fc 5f 11 2c b7 f1 e7
00:32:15.642: amai: : b5 d7 d3 3b 3c 98 c2 28
00:32:15.693: amai: : -----------------------------------------------
00:32:15.744: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 104 bytes]
00:32:15.800: amai: : 30 00 00 00 02 00 00 00 79 fd 9f bc b9 03 2a b6
00:32:15.850: amai: : 83 f5 8f 50 37 10 33 6f 71 12 ae 84 98 16 36 8a
00:32:15.902: amai: : b0 8a 55 1f 9b a9 4f c0 d4 b2 30 e2 cf 71 8d e2
00:32:15.953: amai: : af 1d f3 ea d5 f0 78 84 cc fe 3d e5 78 a1 a3 ef
00:32:16.004: amai: : 2d f2 6e 55 1b fb 44 42 d9 aa 61 95 71 86 a9 9a
00:32:16.054: amai: : f7 ea 15 d9 ef d7 72 1f 9e 11 02 98 46 3f dd c6
00:32:16.105: amai: : 8d ec 29 fd 15 a4 5a d5
00:32:16.156: amai: : -----------------------------------------------
00:32:16.207: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 536 bytes]
00:32:16.257: amai: : 30 00 00 00 0b 00 00 00 c8 02 f2 25 ea 27 bd af
00:32:16.308: amai: : db 2d d5 07 60 b2 2b 9d 5f df b7 26 26 30 7c 59
00:32:16.359: amai: : 80 bc b1 40 42 61 93 f5 aa a1 02 19 97 5a 35 af
00:32:16.411: amai: : ba 56 af c0 d5 79 1b 42 1a c9 34 16 75 5f 91 c4
00:32:16.462: amai: : 72 09 ae 34 f8 84 2c c3 5c 2f 55 cf 2d 9e 66 cd
00:32:16.513: amai: : 7c 48 10 71 4b b5 c1 c9 de a1 24 cb 11 0d 85 c2
00:32:16.564: amai: : ff 8f 01 ab 1d d6 a2 97 1b d4 69 a9 54 fe de 3a
00:32:16.615: amai: : 83 7f 8c 64 a7 8e a5 0b 8f 93 88 3a 41 ae 2b 28
00:32:16.666: amai: : 15 49 40 d6 19 38 c3 f0 e2 1b 1e 6e 81 d0 07 73
00:32:16.718: amai: : 10 da 1b c3 65 d9 a2 db 8b a0 37 db 69 91 78 77
00:32:16.768: amai: : 5e fd 83 da 84 b1 2d bd f6 68 d5 db f4 c0 17 48
00:32:16.819: amai: : 52 cb 07 09 53 7e 68 06 b7 ee 91 18 c7 5a f1 a0
00:32:16.870: amai: : cb e5 10 55 ef 4c 04 dd 99 6a 0d 9c 37 62 04 73
00:32:16.922: amai: : 4f 37 00 df fe f8 27 20 40 e8 77 55 d3 71 ae a9
00:32:16.973: amai: : a9 8c c0 61 5b e0 06 d1 02 df bb d7 54 63 85 0e
00:32:17.023: amai: : 25 c5 50 79 60 c1 95 fe d6 98 58 88 d8 89 ff 3e
00:32:17.075: amai: : 5b 92 81 a6 82 7e fb 0c a0 d0 97 f4 32 0b 3a 7a
00:32:17.126: amai: : 4a ac d0 ee ff 81 cf 4d cc 34 30 07 d0 09 22 11
00:32:17.177: amai: : 1b 00 6b ae c9 b4 e7 96 a5 5e ff 0e 08 d0 c4 65
00:32:17.228: amai: : 93 e6 4e 4f f7 09 a0 e9 0e a7 b5 53 76 ef 5f f4
00:32:17.283: amai: : b6 86 e8 5b fd e7 04 81 58 a6 5c ff c0 6c 73 6a
00:32:17.334: amai: : da 00 d1 4f fe 15 5d 8b 9a 69 3c a6 71 6a cc 6b
00:32:17.385: amai: : 7c 75 63 d9 85 e7 71 5a ff ea 56 8a 61 56 52 5f
00:32:17.435: amai: : 6d ba ac b4 9e a0 a5 65 f2 2c ab 6e 9b 8e 79 9e
00:32:17.486: amai: : 6b f4 77 3b 46 54 84 1a e8 50 fa b6 93 5d 4b b9
00:32:17.537: amai: : 36 1d 19 46 fd 4b 56 ca 3d 86 ee 48 d8 6e 38 4c
00:32:17.588: amai: : 7e 90 0f 96 f3 6b de 22 c8 a2 d9 69 76 6a b6 a2
00:32:17.639: amai: : b9 a2 c1 9c f8 76 8d f9 00 d2 88 b7 ca 44 ae 1c
00:32:17.690: amai: : a9 6a 3d b5 d5 c5 75 63 9b 86 de 5e 29 cd 26 45
00:32:17.741: amai: : 3d af 7c 1a 54 a5 b0 f3 14 46 1d a8 1c ae ee de
00:32:17.792: amai: : ea 44 4f 21 0f 0a db fb d0 5e 60 5d f0 6f aa 90
00:32:17.843: amai: : ac 20 dd 3a fa bf 33 b0 21 86 42 06 4b fa 8f 00
00:32:17.894: amai: : 41 c7 8a e1 c1 51 92 9d 22 a6 4e c3 b1 f9 c4 d4
00:32:17.945: amai: : 04 ea ec e5 ac 35 8d 00
00:32:17.996: amai: : -----------------------------------------------
00:32:18.047: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 344 bytes]
00:32:18.098: amai: : 30 00 00 00 07 00 00 00 30 d7 6f 8c 4e bf ed ed
00:32:18.149: amai: : d7 4c a0 cb c0 57 14 ba 2a c6 b9 00 06 45 df 39
00:32:18.201: amai: : a7 4f 6a 6f f0 9f 7b d6 2e 83 90 7a 73 83 4e 2e
00:32:18.252: amai: : ec ec cf 7f 92 bf 99 73 c5 16 aa 8d 3b 45 7c 63
00:32:18.303: amai: : 6c 68 26 93 70 99 c0 d2 3a 13 f2 c3 70 1a 38 8b
00:32:18.354: amai: : 3c 8f e4 bc 20 73 28 1b 0c 44 62 61 03 69 88 4c
00:32:18.405: amai: : 4a ba ba 8e 97 b6 de be 9e 3e 94 54 7b 6b 5a a1
00:32:18.456: amai: : 19 38 30 a5 f3 00 2c cd b6 cf d9 54 77 29 f3 a7
00:32:18.507: amai: : 13 3c 74 94 3d 0b b0 59 6c 05 87 f1 97 37 8a d9
00:32:18.558: amai: : df 6c 74 e0 7c 23 d1 a2 c5 16 aa 8d 3b 45 7c 63
00:32:18.609: amai: : 6c 68 26 93 70 99 c0 d2 3a 13 f2 c3 70 1a 38 8b
00:32:18.669: amai: : 3c 8f e4 bc 20 73 28 1b 0c 44 62 61 03 69 88 4c
00:32:18.720: amai: : 4a ba ba 8e 97 b6 de be f7 f1 e2 e2 9b 40 85 92
00:32:18.771: amai: : e9 a4 f8 85 44 de 3c 3c d6 4a 69 14 88 e4 56 30
00:32:18.823: amai: : 16 d8 5a fc bc 5b fe 8e 23 bd e5 6a 05 fd 11 9c
00:32:18.874: amai: : 57 89 16 67 0c a1 bf 7b fc 11 28 49 0c 92 f9 7c
00:32:18.926: amai: : 76 8f 31 74 24 c5 c5 34 e7 25 f7 76 42 84 d1 cf
00:32:18.977: amai: : 1c 7b fe f6 9b a1 ee 9e 5d 5f e7 34 ed 6a af d5
00:32:19.028: amai: : 22 a9 13 7c df 74 88 f2 d1 3e 6a d9 0e ae 0a 61
00:32:19.079: amai: : 1f 8a 55 28 4b e5 11 3b c9 1c 3b 94 a2 c8 d7 21
00:32:19.130: amai: : 19 7d 98 c9 17 1d 63 76 67 ae 91 95 f2 14 69 24
00:32:19.181: amai: : 78 11 dc 12 73 ea 5d ac
00:32:19.232: amai: : -----------------------------------------------
00:32:19.293: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 680 bytes]
00:32:19.344: amai: : 30 00 00 00 0e 00 00 00 4f 01 10 c8 21 80 97 1f
00:32:19.395: amai: : b4 50 59 c9 b0 9b 6b ff 9a 72 a3 d3 3d 81 07 46
00:32:19.447: amai: : 9a 3d 2f 75 09 a8 6e ad 45 aa 81 a8 9d 9a 5e ef
00:32:19.498: amai: : 1f 0c 9e d4 97 8a d9 3a eb 9f f0 b1 47 aa b3 5d
00:32:19.548: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:32:19.599: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:32:19.650: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:32:19.701: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:32:19.751: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:32:19.802: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:32:19.853: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:32:19.904: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:32:19.955: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:32:20.006: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:32:20.057: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:32:20.109: amai: : 83 c8 b9 42 91 dd 6f aa f7 f0 da 04 88 29 b8 43
00:32:20.159: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:32:20.210: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:32:20.262: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:32:20.313: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:32:20.364: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:32:20.415: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:32:20.466: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:32:20.516: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:32:20.567: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:32:20.618: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:32:20.670: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:32:20.721: amai: : fc 40 88 5f 79 a0 20 89 14 a4 e9 8d e5 90 b2 b8
00:32:20.772: amai: : f9 12 c9 5a ef 91 70 49 52 2f 91 86 4b e3 fb 9d
00:32:20.823: amai: : c3 34 4a b1 31 53 fb 0e 00 04 4f 08 2b af f1 13
00:32:20.874: amai: : ff f7 37 ae e8 31 a6 b1 40 7e a2 ec 68 0c 19 11
00:32:20.924: amai: : 85 5a 2c 49 a9 16 33 e3 b9 4f 5c 0d cf bc 46 ae
00:32:20.975: amai: : 5f bc 42 3d b6 c1 08 bb eb 57 6b c6 33 da 5b a4
00:32:21.027: amai: : 2f e0 e8 cb 73 91 ca 28 49 a1 4b d4 f5 b4 a1 f4
00:32:21.078: amai: : 97 8a 93 9c 75 37 27 33 65 07 ab 50 37 66 30 a8
00:32:21.129: amai: : e5 01 e9 94 ff e0 7a eb 0d 2c 4d 58 22 5b e7 0a
00:32:21.180: amai: : 71 ec 46 a2 aa 04 8d 26 ef dc 34 80 82 fe 22 e8
00:32:21.231: amai: : 35 dd 1a 45 53 9a 56 c1 53 1b df c3 77 f5 9c 9e
00:32:21.282: amai: : c0 00 90 d7 34 a6 bc 17 b9 cd 73 70 e7 2a ae 31
00:32:21.334: amai: : 80 b7 c8 1e 50 b1 ce 72 9d e7 f6 bd cb 55 bd a8
00:32:21.385: amai: : 2f 7f 62 d4 7a 01 da 6a db f7 db ee 86 77 2b 6d
00:32:21.436: amai: : 1e 1e 67 ef 2c ac d7 63 56 f3 90 7d 96 86 2c 82
00:32:21.487: amai: : 2a 90 e0 ec 1f da 40 c3
00:32:21.538: amai: : -----------------------------------------------
00:32:21.588: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 248 bytes]
00:32:21.638: amai: : 30 00 00 00 05 00 00 00 57 ad 80 ac 99 4f 9c 5a
00:32:21.690: amai: : 2b 62 11 14 f4 fe 61 a3 6f 52 0a 61 bf 48 75 ff
00:32:21.740: amai: : ea de 86 71 17 88 8e d1 31 8e 9f 8b 66 e7 37 be
00:32:21.792: amai: : 5f fa 44 46 b8 5f 1a 2a 44 88 de db cd 51 3b bd
00:32:21.842: amai: : 23 6c 05 01 48 42 34 74 2c a3 14 c5 c7 d4 1f d6
00:32:21.893: amai: : 06 c7 e2 a9 a1 96 e2 76 0f 9f d7 83 2b ed 88 b3
00:32:21.945: amai: : 65 6f b6 0f ad 8d b4 f3 9f 85 a8 c7 d4 ad 4c 6c
00:32:21.996: amai: : b7 95 f1 2b 25 df 6e 70 d0 b6 02 59 54 9a a7 27
00:32:22.047: amai: : 79 fd e2 6f 13 83 f4 f7 42 ba 57 47 6e ba a7 0f
00:32:22.098: amai: : f3 9c b9 2f 23 eb 17 6e 0c fe 11 2c 08 c9 bc e3
00:32:22.150: amai: : 48 32 0a 23 4e b8 77 51 04 3f 4e ab 8e 7d 39 cf
00:32:22.200: amai: : ae 7b 5c 2f 1e 08 f2 e4 49 b5 90 c4 78 43 01 1c
00:32:22.252: amai: : b5 e8 73 c0 78 59 ed 49 d3 41 e0 3e 26 0e 5a 36
00:32:22.303: amai: : 76 29 21 ab 35 9e 00 6b 8d 92 9b fc 55 85 31 96
00:32:22.354: amai: : 61 c5 7b 3d 31 a5 c8 2b c4 fb 9c 9c fd b1 8e 89
00:32:22.405: amai: : 1b 2b e5 35 b7 2e fd 47
00:32:22.456: amai: : -----------------------------------------------
00:32:22.507: amai: BbfwReaderFindAndCopyFileData: failed to find bbfw item "vinyl/update/main/signedprofile.der": File error
00:32:22.558: amai: BbfwReaderFindAndCopyFileData: failed to find bbfw item "vinyl/update/gold/signedprofile.der": File error
00:32:22.610: amai: AMAuthInstallIsICE19BBGoldCertIDECDSA: GoldCertId: 1F3F5BDF
00:32:22.660: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BasebandFirmware to Manifest to personalize later
00:32:22.711: amai: _AMAuthInstallVinylCreateMeasurementsInternal: [eUICC IM4P: 367 bytes]
00:32:22.763: amai: : 30 82 01 6b 16 04 49 4d 34 50 16 04 65 75 69 67
00:32:22.814: amai: : 16 03 31 2e 30 04 82 01 56 30 82 01 52 30 38 04
00:32:22.865: amai: : 14 41 58 4a fd 3e 44 7c 10 db 18 47 70 31 f5 38
00:32:22.915: amai: : da ee d0 c7 d3 04 20 1e be 22 4e ea fb 19 89 d1
00:32:22.967: amai: : 20 7c 19 0c 84 a2 d6 30 8a 5a 24 c5 c7 29 93 7b
00:32:23.018: amai: : 62 5a 97 97 22 7d c3 30 44 04 20 d5 c4 4a af d2
00:32:23.069: amai: : cc 60 30 75 64 0c ec 16 0c 8a f0 44 60 78 c3 a8
00:32:23.120: amai: : 55 bc 8c 9f d9 f2 cf b0 06 4e dc 04 20 5a 20 4e
00:32:23.171: amai: : a6 96 d2 b8 f2 9c 41 cf 48 fc 61 bb 4f 3c c8 02
00:32:23.222: amai: : f2 47 bd f9 53 80 49 6e 6e f1 9e 92 2d 30 44 04
00:32:23.273: amai: : 20 e1 2a 06 d7 c9 ac c1 96 66 32 3b ae 14 44 e3
00:32:23.324: amai: : fe 8c 02 10 40 61 85 c6 9d cd 08 de a7 06 62 b7
00:32:23.376: amai: : 62 04 20 97 e5 ee 2b 80 7d 08 42 5c 4e 8f a5 20
00:32:23.428: amai: : e1 bf 4f a7 fc 16 a1 f0 ae 97 92 ba 90 e4 60 f6
00:32:23.487: amai: : c3 2e a3 30 44 04 20 e1 b1 da f1 53 9e 54 f1 b5
00:32:23.538: amai: : 98 3f e2 aa 2c 79 08 c1 e7 80 50 2b fd 2a 10 59
00:32:23.590: amai: : e7 36 8f f3 30 2a 99 04 20 33 22 59 89 3c 2d dd
00:32:23.641: amai: : 78 5a 3f 6a 31 7a f8 23 ef 9c b7 67 3b fc 3d 5f
00:32:23.692: amai: : c7 05 0a a1 72 57 61 34 ab 30 44 04 20 f3 45 aa
00:32:23.744: amai: : f5 0d 4e 71 74 44 2a 7d 91 1d 98 f3 eb 21 cc 36
00:32:23.795: amai: : ac f8 d6 2a e7 48 cd 98 93 46 fb 9b ae 04 20 a1
00:32:23.846: amai: : 25 45 13 47 c7 d2 32 bf 54 ea 81 06 b9 5f 43 3e
00:32:23.897: amai: : 5d 99 e8 c7 d5 64 bc e0 c6 f1 69 cd d7 2d 80
00:32:23.948: amai: : -----------------------------------------------
00:32:23.999: amai: _AMAuthInstallVinylCreateMeasurementsInternal: [eUICC IM4P: 367 bytes]
00:32:24.057: amai: : 30 82 01 6b 16 04 49 4d 34 50 16 04 65 75 69 6d
00:32:24.108: amai: : 16 03 31 2e 30 04 82 01 56 30 82 01 52 30 38 04
00:32:24.159: amai: : 14 41 58 4a fd 3e 44 7c 10 db 18 47 70 31 f5 38
00:32:24.210: amai: : da ee d0 c7 d3 04 20 6d da 08 fb 44 c2 af 07 2b
00:32:24.261: amai: : 83 f5 69 3f 1a f7 31 08 b6 9a 13 1c 4b 47 be d9
00:32:24.312: amai: : 7c fa 07 0f 5e a5 a8 30 44 04 20 d5 c4 4a af d2
00:32:24.366: amai: : cc 60 30 75 64 0c ec 16 0c 8a f0 44 60 78 c3 a8
00:32:24.418: amai: : 55 bc 8c 9f d9 f2 cf b0 06 4e dc 04 20 f8 81 b2
00:32:24.469: amai: : 30 0e 1c e7 e4 8e 6f fb d9 11 51 7a 52 e2 3c 0d
00:32:24.520: amai: : 5e e7 54 18 e0 61 78 fe 08 d0 82 0c 5f 30 44 04
00:32:24.571: amai: : 20 e1 2a 06 d7 c9 ac c1 96 66 32 3b ae 14 44 e3
00:32:24.625: amai: : fe 8c 02 10 40 61 85 c6 9d cd 08 de a7 06 62 b7
00:32:24.675: amai: : 62 04 20 d4 24 40 59 ca b0 ad a1 69 dc 52 33 de
00:32:24.727: amai: : ba 0c ad f4 45 02 89 41 6a d7 61 4a 8f f0 fa 9e
00:32:24.779: amai: : 48 04 64 30 44 04 20 e1 b1 da f1 53 9e 54 f1 b5
00:32:24.831: amai: : 98 3f e2 aa 2c 79 08 c1 e7 80 50 2b fd 2a 10 59
00:32:24.889: amai: : e7 36 8f f3 30 2a 99 04 20 53 46 d0 a8 9e f6 36
00:32:24.942: amai: : 23 a2 38 8b ae 7b e6 1e 9b ab f8 73 27 1f 9b 59
00:32:24.993: amai: : e3 74 f1 08 5e 8b 6e 99 33 30 44 04 20 f3 45 aa
00:32:25.044: amai: : f5 0d 4e 71 74 44 2a 7d 91 1d 98 f3 eb 21 cc 36
00:32:25.096: amai: : ac f8 d6 2a e7 48 cd 98 93 46 fb 9b ae 04 20 71
00:32:25.146: amai: : 34 da 57 d6 15 27 67 45 e4 35 cf 2d a6 6e f7 60
00:32:25.200: amai: : 63 8b 5d cd b8 36 8f 64 a7 7d 18 bf 31 70 58
00:32:25.251: amai: : -----------------------------------------------
00:32:25.301: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting eUICC,Main to Manifest to personalize later
00:32:25.353: amai: _AMAuthInstallVinylCreateMeasurementsInternal: [eUICC IM4P: 367 bytes]
00:32:25.403: amai: : 30 82 01 6b 16 04 49 4d 34 50 16 04 65 75 69 67
00:32:25.454: amai: : 16 03 31 2e 30 04 82 01 56 30 82 01 52 30 38 04
00:32:25.505: amai: : 14 41 58 4a fd 3e 44 7c 10 db 18 47 70 31 f5 38
00:32:25.556: amai: : da ee d0 c7 d3 04 20 1e be 22 4e ea fb 19 89 d1
00:32:25.607: amai: : 20 7c 19 0c 84 a2 d6 30 8a 5a 24 c5 c7 29 93 7b
00:32:25.658: amai: : 62 5a 97 97 22 7d c3 30 44 04 20 d5 c4 4a af d2
00:32:25.725: amai: : cc 60 30 75 64 0c ec 16 0c 8a f0 44 60 78 c3 a8
00:32:25.781: amai: : 55 bc 8c 9f d9 f2 cf b0 06 4e dc 04 20 5a 20 4e
00:32:25.832: amai: : a6 96 d2 b8 f2 9c 41 cf 48 fc 61 bb 4f 3c c8 02
00:32:25.884: amai: : f2 47 bd f9 53 80 49 6e 6e f1 9e 92 2d 30 44 04
00:32:25.935: amai: : 20 e1 2a 06 d7 c9 ac c1 96 66 32 3b ae 14 44 e3
00:32:25.986: amai: : fe 8c 02 10 40 61 85 c6 9d cd 08 de a7 06 62 b7
00:32:26.037: amai: : 62 04 20 97 e5 ee 2b 80 7d 08 42 5c 4e 8f a5 20
00:32:26.089: amai: : e1 bf 4f a7 fc 16 a1 f0 ae 97 92 ba 90 e4 60 f6
00:32:26.139: amai: : c3 2e a3 30 44 04 20 e1 b1 da f1 53 9e 54 f1 b5
00:32:26.191: amai: : 98 3f e2 aa 2c 79 08 c1 e7 80 50 2b fd 2a 10 59
00:32:26.241: amai: : e7 36 8f f3 30 2a 99 04 20 33 22 59 89 3c 2d dd
00:32:26.292: amai: : 78 5a 3f 6a 31 7a f8 23 ef 9c b7 67 3b fc 3d 5f
00:32:26.347: amai: : c7 05 0a a1 72 57 61 34 ab 30 44 04 20 f3 45 aa
00:32:26.398: amai: : f5 0d 4e 71 74 44 2a 7d 91 1d 98 f3 eb 21 cc 36
00:32:26.456: amai: : ac f8 d6 2a e7 48 cd 98 93 46 fb 9b ae 04 20 a1
00:32:26.508: amai: : 25 45 13 47 c7 d2 32 bf 54 ea 81 06 b9 5f 43 3e
00:32:26.559: amai: : 5d 99 e8 c7 d5 64 bc e0 c6 f1 69 cd d7 2d 80
00:32:26.612: amai: : -----------------------------------------------
00:32:26.666: amai: _AMAuthInstallVinylCreateMeasurementsInternal: [eUICC IM4P: 367 bytes]
00:32:26.719: amai: : 30 82 01 6b 16 04 49 4d 34 50 16 04 65 75 69 6d
00:32:26.772: amai: : 16 03 31 2e 30 04 82 01 56 30 82 01 52 30 38 04
00:32:26.824: amai: : 14 41 58 4a fd 3e 44 7c 10 db 18 47 70 31 f5 38
00:32:26.874: amai: : da ee d0 c7 d3 04 20 6d da 08 fb 44 c2 af 07 2b
00:32:26.925: amai: : 83 f5 69 3f 1a f7 31 08 b6 9a 13 1c 4b 47 be d9
00:32:26.977: amai: : 7c fa 07 0f 5e a5 a8 30 44 04 20 d5 c4 4a af d2
00:32:27.028: amai: : cc 60 30 75 64 0c ec 16 0c 8a f0 44 60 78 c3 a8
00:32:27.079: amai: : 55 bc 8c 9f d9 f2 cf b0 06 4e dc 04 20 f8 81 b2
00:32:27.144: amai: : 30 0e 1c e7 e4 8e 6f fb d9 11 51 7a 52 e2 3c 0d
00:32:27.195: amai: : 5e e7 54 18 e0 61 78 fe 08 d0 82 0c 5f 30 44 04
00:32:27.246: amai: : 20 e1 2a 06 d7 c9 ac c1 96 66 32 3b ae 14 44 e3
00:32:27.296: amai: : fe 8c 02 10 40 61 85 c6 9d cd 08 de a7 06 62 b7
00:32:27.350: amai: : 62 04 20 d4 24 40 59 ca b0 ad a1 69 dc 52 33 de
00:32:27.402: amai: : ba 0c ad f4 45 02 89 41 6a d7 61 4a 8f f0 fa 9e
00:32:27.453: amai: : 48 04 64 30 44 04 20 e1 b1 da f1 53 9e 54 f1 b5
00:32:27.504: amai: : 98 3f e2 aa 2c 79 08 c1 e7 80 50 2b fd 2a 10 59
00:32:27.555: amai: : e7 36 8f f3 30 2a 99 04 20 53 46 d0 a8 9e f6 36
00:32:27.609: amai: : 23 a2 38 8b ae 7b e6 1e 9b ab f8 73 27 1f 9b 59
00:32:27.661: amai: : e3 74 f1 08 5e 8b 6e 99 33 30 44 04 20 f3 45 aa
00:32:27.720: amai: : f5 0d 4e 71 74 44 2a 7d 91 1d 98 f3 eb 21 cc 36
00:32:27.850: amai: : ac f8 d6 2a e7 48 cd 98 93 46 fb 9b ae 04 20 71
00:32:27.900: amai: : 34 da 57 d6 15 27 67 45 e4 35 cf 2d a6 6e f7 60
00:32:27.964: amai: : 63 8b 5d cd b8 36 8f 64 a7 7d 18 bf 31 70 58
00:32:28.018: amai: : -----------------------------------------------
00:32:28.069: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting eUICC,Gold to Manifest to personalize later
00:32:28.120: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting OS to Manifest to personalize later
00:32:28.172: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RecoveryMode to Manifest to personalize later
00:32:28.223: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Liquid to Manifest to personalize later
00:32:28.274: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow0 to Manifest to personalize later
00:32:28.325: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AVE to Manifest to personalize later
00:32:28.377: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ANE to Manifest to personalize later
00:32:28.458: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,HapticAssets to Manifest to personalize later
00:32:28.509: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryPlugin to Manifest to personalize later
00:32:28.560: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreSEP to Manifest to personalize later
00:32:28.625: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ISP to Manifest to personalize later
00:32:28.676: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SEP to Manifest to personalize later
00:32:28.727: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBoot to Manifest to personalize later
00:32:28.778: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreTrustCache to Manifest to personalize later
00:32:28.829: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet1 to Manifest to personalize later
00:32:28.881: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting DeviceTree to Manifest to personalize later
00:32:28.931: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AudioCodecFirmware to Manifest to personalize later
00:32:28.982: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting PMP to Manifest to personalize later
00:32:29.033: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LeapHaptics to Manifest to personalize later
00:32:29.084: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting StaticTrustCache to Manifest to personalize later
00:32:29.136: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging0 to Manifest to personalize later
00:32:29.187: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LLB to Manifest to personalize later
00:32:29.238: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow1 to Manifest to personalize later
00:32:29.289: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryFull to Manifest to personalize later
00:32:29.340: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AppleLogo to Manifest to personalize later
00:32:29.391: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SIO to Manifest to personalize later
00:32:29.442: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging1 to Manifest to personalize later
00:32:29.536: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting GFX to Manifest to personalize later
00:32:29.591: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AOP to Manifest to personalize later
00:32:29.641: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet0 to Manifest to personalize later
00:32:29.692: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting WCHFirmwareUpdater to Manifest to personalize later
00:32:29.744: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Multitouch to Manifest to personalize later
00:32:29.794: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbProvisioningManifestKeyHash = <CFDa
                     ta 0x7f9603c406a0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x238c5118db979840969fb4dba3ab2db3 ... 162
                     9e2a30e1df392}
00:32:29.845: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbActivationManifestKeyHash = <CFData
                     0x7f9603c40210 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x1b41607650ebf11c6b39f41cb267dc64 ... 055803e
                     1ef81c870}
00:32:29.896: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbFDRSecurityKeyHash = <CFData 0x7f9
                     603c40510 [0x7fff88086cc0]>{length = 0, capacity = 0, bytes = 0x}
00:32:29.947: amai: _AMAuthInstallBundleCreateServerRequestDictionary: ticketPath amai/apimg4ticket.der , withApTicket is True,  (!False
                     && ( True || False))
00:32:30.000: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "RestoreLogo" Digest = "<CFData 0x7f9603c0ebe
                     0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x3872f1d458a55e434f1c50aa50206d5e ... d69ffc73b53132d8}"
00:32:30.051: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "RestoreDeviceTree" Digest = "<CFData 0x7f9603
                     c47020 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xb6d483531372926e5107cc0fe829d268 ... 9153abfcb4b77
                     dbe}"
00:32:30.101: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "RestoreKernelCache" Digest = "<CFData 0x7f960
                     3d7f8e0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x0f7d8151c75ca59a5e635b46255a1457 ... a66dad05ec54
                     6a5c}"
00:32:30.153: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "RestoreRamDisk" Digest = "<CFData 0x7f9603d7
                     fb00 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x0f6de1be91270479bac3b5f57a306c61 ... a315f014a2922f73}
                     "
00:32:30.204: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "OSRamdisk" not part of manifest, skipping
00:32:30.256: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "iBEC" Digest = "<CFData 0x7f9603c3fcf0 [0x7fff
                     88086cc0]>{length = 48, capacity = 48, bytes = 0x8e5299aee398f292dd9bd19c46077a2c ... 12fa7601087dce52}"
00:32:30.307: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "iBSS" Digest = "<CFData 0x7f9603c40760 [0x7ff
                     f88086cc0]>{length = 48, capacity = 48, bytes = 0x900016565cae354601a6f01d64262f52 ... 044bba9169a14d7d}"
00:32:30.358: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "KernelCache" Digest = "<CFData 0x7f9603c4139
                     0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xa7e50e911a1456f387077304f546703c ... 972361c56a01127c}"
00:32:30.409: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "ftap"
00:32:30.461: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "rfta"
00:32:30.529: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "ftsp"
00:32:30.580: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "rfts"
00:32:30.631: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "Ap,SystemVolumeCanonicalMetadata" Digest = "<
                     CFData 0x7f9603d7fb70 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x67cee499a988225be3bbb500d9dca3b1 
                     ... eb00e45838d93538}"
00:32:30.682: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolumeCanonicalMetadata" not part of manif
                     est, skipping
00:32:30.732: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "BaseSystemVolume" not part of manifest, skipping
00:32:30.783: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,BaseSystemVolume" not part of manifest, skipping
00:32:30.835: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "SystemVolume" Digest = "<CFData 0x7f9603d7fb
                     e0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xa7ea9c8ba170f5e8af41ff395adc22ce ... 84adc85776d467ce}"
00:32:30.886: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolume" not part of manifest, skipping
00:32:30.951: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Ap,BaseSystemTrustCache" not part of manifest, skipping
00:32:31.002: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Diags" not part of manifest, skipping
00:32:31.053: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "CFELoader" not part of manifest, skipping
00:32:31.105: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "RBM" not part of manifest, skipping
00:32:31.156: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PHLEET" not part of manifest, skipping
00:32:31.207: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PERTOS" not part of manifest, skipping
00:32:31.258: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PEHammer" not part of manifest, skipping
00:32:31.309: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Alamo" not part of manifest, skipping
00:32:31.360: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "eUICC,Main" Digest = "<CFData 0x7f9603d7ff30 
                     [0x7fff88086cc0]>{length = 32, capacity = 32, bytes = 0x83f47a1e683c5e317693beb7db1b47b1 ... 072ae2f821e193d6}"
00:32:31.411: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "eUICC,Gold" Digest = "<CFData 0x7f9603d80440 
                     [0x7fff88086cc0]>{length = 32, capacity = 32, bytes = 0x25e93a6e10862e74e208ce06674263c3 ... 50f31daf4defe566}"
00:32:31.463: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "OS"
00:32:31.514: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "RecoveryMode" Digest = "<CFData 0x7f9603d264
                     70 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xa65af1c2116bea307c7a3d851f020240 ... e5d8a162d824e055}"
00:32:31.564: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "Liquid" Digest = "<CFData 0x7f9603d7fd40 [0x7f
                     ff88086cc0]>{length = 48, capacity = 48, bytes = 0x6acf886bcd4e0f984f2d08deac30c4e4 ... b2f7bb013c565be9}"
00:32:31.616: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "BatteryLow0" Digest = "<CFData 0x7f9603c61550
                     [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x14d4e4ed07bdc3ae4d7d395fe5615561 ... 3cafb6f879880730}"
00:32:31.666: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "AVE" Digest = "<CFData 0x7f9603c3bb70 [0x7fff
                     88086cc0]>{length = 48, capacity = 48, bytes = 0x123f9a0fd76c16fd9f678d3deef827a4 ... b228950b493f8fb1}"
00:32:31.717: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "ANE" Digest = "<CFData 0x7f9603c61420 [0x7fff8
                     8086cc0]>{length = 48, capacity = 48, bytes = 0x8c098accc817873dac5c77beb3fe327d ... 92e0d9b9a4d5fe08}"
00:32:31.768: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "Ap,HapticAssets" Digest = "<CFData 0x7f9603c6
                     1920 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xab7ff7dec045af6824f5863200a7a7dc ... 63fbde79e8e7aecc
                     }"
00:32:31.819: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "BatteryPlugin" Digest = "<CFData 0x7f9603d272c
                     0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x97a5715815c5ca83d5a76f0822e6e05e ... 7da94e91b3956130}"
00:32:31.871: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "RestoreSEP" Digest = "<CFData 0x7f9603d25f40
                     [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x697f3d19a31a2ddb64134279da47c26e ... e347df8c937791d6}"
00:32:31.922: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "ISP" Digest = "<CFData 0x7f9603c619f0 [0x7fff8
                     8086cc0]>{length = 48, capacity = 48, bytes = 0x98a91c26c48e194480867726e673a559 ... 9fd9c934fcd872d1}"
00:32:31.973: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "SEP" Digest = "<CFData 0x7f9603c436e0 [0x7fff
                     88086cc0]>{length = 48, capacity = 48, bytes = 0x7caf52246b0c9fec55d47ffba919d03c ... 39a2b257f8efd318}"
00:32:32.024: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "iBoot" Digest = "<CFData 0x7f9603d262a0 [0x7f
                     ff88086cc0]>{length = 48, capacity = 48, bytes = 0x044935e124953edd2d4add2d8ee5b069 ... a6d65d963ca32108}"
00:32:32.075: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "RestoreTrustCache" Digest = "<CFData 0x7f9603
                     c43590 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xea2f64660e5581c498ef335e2fcfb408 ... 490a2c54bddd17
                     ea}"
00:32:32.127: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "LowPowerWallet1" Digest = "<CFData 0x7f9603d
                     263c0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x69e4c777fbebdb98f64440e802da9b31 ... 3a5946aa60b495
                     02}"
00:32:32.178: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "DeviceTree" Digest = "<CFData 0x7f9603d27250
                     [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x80dc618d0f224a5ddc9a9f6b20ab46de ... 1c88d458e1b4189c}"
00:32:32.229: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "AudioCodecFirmware" Digest = "<CFData 0x7f96
                     03c43600 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x8acd7cfabd4adede08d3bae894fcabe2 ... 8be88518fce
                     49b17}"
00:32:32.280: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "PMP" Digest = "<CFData 0x7f9603d808a0 [0x7f
                     ff88086cc0]>{length = 48, capacity = 48, bytes = 0x26e9466b7e3d13500c54a9e4c65ea861 ... db5e37f635382936}"
00:32:32.331: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "LeapHaptics" Digest = "<CFData 0x7f9603c4367
                     0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x1602620cf252593517bfa56851472272 ... b02695270e52f1a4}"
00:32:32.382: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "StaticTrustCache" Digest = "<CFData 0x7f9603d
                     25e60 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x00884efe771b7735e224bb5c5e9cc41f ... 1f207ca0342cfe5
                     8}"
00:32:32.433: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "BatteryCharging0" Digest = "<CFData 0x7f9603c
                     437c0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x72be5aae6d22678cdbf5399d58da2888 ... 297bfe7fa18c59
                     f5}"
00:32:32.485: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "LLB" Digest = "<CFData 0x7f9603c43a10 [0x7fff
                     88086cc0]>{length = 48, capacity = 48, bytes = 0x1c436bf011affca7e582421dd06fab01 ... 6fcdbd21bfdef94d}"
00:32:32.536: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "BatteryLow1" Digest = "<CFData 0x7f9603d26ed
                     0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x17786c080a237ac27066bbd640dbea32 ... b3de1b92555636ab}"

00:32:32.586: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "BatteryFull" Digest = "<CFData 0x7f9603c43830
                     [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xd9464eb7c55d777306e1b315e29bc3f7 ... 21f909a038db32d9}"
00:32:32.638: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "AppleLogo" Digest = "<CFData 0x7f9603c43b20
                     [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x563ddf9896b66e3998cbdd3ef5e8a34f ... be99131bb80753a1}"
00:32:32.689: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "SIO" Digest = "<CFData 0x7f9603c43a80 [0x7fff
                     88086cc0]>{length = 48, capacity = 48, bytes = 0x7bdda0c50811976822035f2cd356ba20 ... 98df96bb8598f31f}"
00:32:32.739: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "BatteryCharging1" Digest = "<CFData 0x7f9603c
                     43b90 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x9f804fb9a09de1629093f678a3c36cdd ... 3dc894ccaa8470
                     33}"
00:32:32.791: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "GFX" Digest = "<CFData 0x7f9603d80910 [0x7fff
                     88086cc0]>{length = 48, capacity = 48, bytes = 0xeddb961a487f1b97334e5250456f8314 ... bc61fbeaf65e36c9}"
00:32:32.841: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "AOP" Digest = "<CFData 0x7f9603d26e50 [0x7ff
                     f88086cc0]>{length = 48, capacity = 48, bytes = 0xe5f2bb63c9aba5339ada5a4c93521414 ... e8632ad38065196a}"
00:32:32.893: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "LowPowerWallet0" Digest = "<CFData 0x7f9603c
                     438a0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xfbdaaf972b183a231418d30087329878 ... 3b5d46a324a8c0
                     28}"
00:32:32.944: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "WCHFirmwareUpdater" Digest = "<CFData 0x7f9
                     603c43940 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xbd8fc8b761603bf197ff809d8f43e172 ... d5c621a90f79
                     7ca0}"
00:32:32.995: amai: _AMAuthInstallBundleCreateServerRequestDictionary: personalizing "Multitouch" Digest = "<CFData 0x7f9603c43d20
                     [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0xcb9a3cdba78fec5e99e0702bbc243793 ... 42ca3b8707b8dc23}"
00:32:33.046: amai: AMSupportPlatformCreateBufferFromNativeFilePath: open failed: No such file or directory
00:32:33.097: amai: AMSupportPlatformCreateBufferFromNativeFilePath: /usr/local/standalone/firmware/device_map.plist
00:32:33.148: amai: AMAuthInstallApCopyDeviceEntryFromDeviceMap: Failed to read devicemap from file:///usr/local/standalone/firmwar
                     e/device_map.plist
00:32:33.199: amai: AMAuthInstallApImg4ServerRequestAddUIDMode: Could not check if UID mode is required.
00:32:33.250: amai: AMAuthInstallApImg4ServerRequestAddUIDMode: Setting UID mode to false because SEPNonce present.
00:32:33.301: amai: AMAuthInstallBasebandApplyTssOverrides: failed to create CFDictionary from Options.plist Error Domain=NSCocoaErr
                     orDomain Code=3840 "Cannot parse a NULL or zero-length data" UserInfo={NSDebugDescription=Cannot parse a NULL o
                     r zero-length data}
00:32:33.352: amai: _AMAuthInstallBundlePopulateManifestProperties: Copying manifest property UniqueBuildID into request
00:32:33.404: amai: _AMAuthInstallBundlePopulateManifestProperties: Copying manifest property Ap,OSLongVersion into request
00:32:33.455: amai: _AMAuthInstallBundlePopulateManifestProperties: Copying manifest property PearlCertificationRootPub into request
00:32:33.506: amai: _AMAuthInstallBundlePopulateManifestProperties: Copying manifest property Ap,TargetType into request
00:32:33.557: amai: _AMAuthInstallBundlePopulateManifestProperties: Copying manifest property Ap,ProductType into request
00:32:33.608: amai: _AMAuthInstallBundlePopulateManifestProperties: Copying manifest property Ap,SDKPlatform into request
00:32:33.659: amai: _AMAuthInstallBundlePopulateManifestProperties: Copying manifest property Ap,Target into request
00:32:33.710: amai: _AMAuthInstallBundlePopulateManifestProperties: Copying manifest property Ap,ProductMarketingVersion into reques
                     t
00:32:33.761: amai: _AMAuthInstallBundlePopulateManifestProperties: Finished copying manifest entitlements.
00:32:33.812: amai: AMAuthInstallRequestSendSyncWithHeader: SSO function returned NULL and no SSO token was provided, SSO disabl
                     ed.
00:32:33.863: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-request.plist
00:32:33.914: amai: tss_submit_job_with_retry: TSS Connection attempt 1 of 3.  (Will retry if TSS_ERR_SERVER_NOT_REACHABLE.)
00:32:33.966: amai: -[AMSupportStaticURLSession URLSession:didReceiveChallenge:completionHandler:]: Authentication challenge receiv
                     ed.  Method: NSURLAuthenticationMethodServerTrust
00:32:34.017: amai: AMAuthInstallRequestSendSyncWithHeader: received tss response (server version: 2.1.0)
00:32:34.067: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-response.plist
00:32:34.619: t
00:32:52.214: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "OSRamdisk"
00:32:52.781: amai: _AMAuthInstallBundleInstallPersonalizedEntry: entry "ftap" does not require personalization; skipping it
00:32:52.832: amai: _AMAuthInstallBundleInstallPersonalizedEntry: entry "rfta" does not require personalization; skipping it
00:32:52.883: amai: _AMAuthInstallBundleInstallPersonalizedEntry: entry "ftsp" does not require personalization; skipping it
00:32:52.934: amai: _AMAuthInstallBundleInstallPersonalizedEntry: entry "rfts" does not require personalization; skipping it
00:33:07.506: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "x86,SystemVolumeCanonicalMetad
                     ata"
00:33:07.557: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "BaseSystemVolume"
00:33:07.608: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "x86,BaseSystemVolume"
00:33:08.660: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "x86,SystemVolume"
00:33:08.724: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "Ap,BaseSystemTrustCache"
00:33:08.791: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "Diags"
00:33:08.854: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "CFELoader"
00:33:08.906: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "RBM"
00:33:08.957: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "PHLEET"
00:33:09.009: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "PERTOS"
00:33:09.060: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "PEHammer"
00:33:09.111: amai: _AMAuthInstallBundlePopulatePersonalizedBundle: no entry in manifest found for "Alamo"
00:33:09.161: amai: AMAuthInstallIsICE19BBGoldCertIDECDSA: GoldCertId: 1F3F5BDF
00:33:09.213: amai: AMAuthInstallIsICE19BBGoldCertIDECDSA: GoldCertId: 1F3F5BDF
00:33:09.264: amai: _AMAuthInstallMonetStitchFirstStage: Stitch Debug:
00:33:09.380:  StitchAddress: 0x740f700 
00:33:09.431:  64-Byte-Aligned: YES 
00:33:09.482:  128-Byte-Aligned: YES
00:33:09.532: 00:33:09.582: amai: _AMAuthInstallMonetStitchFirstStage: Stitch Debug:
00:33:09.633:  StitchAddress: 0x5171700 
00:33:09.683:  64-Byte-Aligned: YES 
00:33:09.733:  128-Byte-Aligned: YES
00:33:09.784: 00:33:10.096: amai: _AMAuthInstallVinylCreateMeasurementsInternal: [eUICC IM4P: 367 bytes]
00:33:10.185: amai: : 30 82 01 6b 16 04 49 4d 34 50 16 04 65 75 69 67
00:33:10.236: amai: : 16 03 31 2e 30 04 82 01 56 30 82 01 52 30 38 04
00:33:10.288: amai: : 14 41 58 4a fd 3e 44 7c 10 db 18 47 70 31 f5 38
00:33:10.338: amai: : da ee d0 c7 d3 04 20 1e be 22 4e ea fb 19 89 d1
00:33:10.389: amai: : 20 7c 19 0c 84 a2 d6 30 8a 5a 24 c5 c7 29 93 7b
00:33:10.440: amai: : 62 5a 97 97 22 7d c3 30 44 04 20 d5 c4 4a af d2
00:33:10.502: amai: : cc 60 30 75 64 0c ec 16 0c 8a f0 44 60 78 c3 a8
00:33:10.552: amai: : 55 bc 8c 9f d9 f2 cf b0 06 4e dc 04 20 5a 20 4e
00:33:10.602: amai: : a6 96 d2 b8 f2 9c 41 cf 48 fc 61 bb 4f 3c c8 02
00:33:10.653: amai: : f2 47 bd f9 53 80 49 6e 6e f1 9e 92 2d 30 44 04
00:33:10.703: amai: : 20 e1 2a 06 d7 c9 ac c1 96 66 32 3b ae 14 44 e3
00:33:10.754: amai: : fe 8c 02 10 40 61 85 c6 9d cd 08 de a7 06 62 b7
00:33:10.859: amai: : 62 04 20 97 e5 ee 2b 80 7d 08 42 5c 4e 8f a5 20
00:33:10.978: amai: : e1 bf 4f a7 fc 16 a1 f0 ae 97 92 ba 90 e4 60 f6
00:33:11.068: amai: : c3 2e a3 30 44 04 20 e1 b1 da f1 53 9e 54 f1 b5
00:33:11.120: amai: : 98 3f e2 aa 2c 79 08 c1 e7 80 50 2b fd 2a 10 59
00:33:11.171: amai: : e7 36 8f f3 30 2a 99 04 20 33 22 59 89 3c 2d dd
00:33:11.222: amai: : 78 5a 3f 6a 31 7a f8 23 ef 9c b7 67 3b fc 3d 5f
00:33:11.272: amai: : c7 05 0a a1 72 57 61 34 ab 30 44 04 20 f3 45 aa
00:33:11.322: amai: : f5 0d 4e 71 74 44 2a 7d 91 1d 98 f3 eb 21 cc 36
00:33:11.373: amai: : ac f8 d6 2a e7 48 cd 98 93 46 fb 9b ae 04 20 a1
00:33:11.423: amai: : 25 45 13 47 c7 d2 32 bf 54 ea 81 06 b9 5f 43 3e
00:33:11.474: amai: : 5d 99 e8 c7 d5 64 bc e0 c6 f1 69 cd d7 2d 80
00:33:11.525: amai: : -----------------------------------------------
00:33:11.575: amai: _AMAuthInstallVinylCreateMeasurementsInternal: [eUICC IM4P: 367 bytes]
00:33:11.625: amai: : 30 82 01 6b 16 04 49 4d 34 50 16 04 65 75 69 6d
00:33:11.677: amai: : 16 03 31 2e 30 04 82 01 56 30 82 01 52 30 38 04
00:33:11.728: amai: : 14 41 58 4a fd 3e 44 7c 10 db 18 47 70 31 f5 38
00:33:11.779: amai: : da ee d0 c7 d3 04 20 6d da 08 fb 44 c2 af 07 2b
00:33:11.830: amai: : 83 f5 69 3f 1a f7 31 08 b6 9a 13 1c 4b 47 be d9
00:33:11.881: amai: : 7c fa 07 0f 5e a5 a8 30 44 04 20 d5 c4 4a af d2
00:33:11.932: amai: : cc 60 30 75 64 0c ec 16 0c 8a f0 44 60 78 c3 a8
00:33:11.983: amai: : 55 bc 8c 9f d9 f2 cf b0 06 4e dc 04 20 f8 81 b2
00:33:12.034: amai: : 30 0e 1c e7 e4 8e 6f fb d9 11 51 7a 52 e2 3c 0d
00:33:12.085: amai: : 5e e7 54 18 e0 61 78 fe 08 d0 82 0c 5f 30 44 04
00:33:12.137: amai: : 20 e1 2a 06 d7 c9 ac c1 96 66 32 3b ae 14 44 e3
00:33:12.187: amai: : fe 8c 02 10 40 61 85 c6 9d cd 08 de a7 06 62 b7
00:33:12.239: amai: : 62 04 20 d4 24 40 59 ca b0 ad a1 69 dc 52 33 de
00:33:12.290: amai: : ba 0c ad f4 45 02 89 41 6a d7 61 4a 8f f0 fa 9e
00:33:12.341: amai: : 48 04 64 30 44 04 20 e1 b1 da f1 53 9e 54 f1 b5
00:33:12.393: amai: : 98 3f e2 aa 2c 79 08 c1 e7 80 50 2b fd 2a 10 59
00:33:12.444: amai: : e7 36 8f f3 30 2a 99 04 20 53 46 d0 a8 9e f6 36
00:33:12.506: amai: : 23 a2 38 8b ae 7b e6 1e 9b ab f8 73 27 1f 9b 59
00:33:12.557: amai: : e3 74 f1 08 5e 8b 6e 99 33 30 44 04 20 f3 45 aa
00:33:12.609: amai: : f5 0d 4e 71 74 44 2a 7d 91 1d 98 f3 eb 21 cc 36
00:33:12.659: amai: : ac f8 d6 2a e7 48 cd 98 93 46 fb 9b ae 04 20 71
00:33:12.710: amai: : 34 da 57 d6 15 27 67 45 e4 35 cf 2d a6 6e f7 60
00:33:12.767: amai: : 63 8b 5d cd b8 36 8f 64 a7 7d 18 bf 31 70 58
00:33:12.819: amai: : -----------------------------------------------
00:33:12.870: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/
00:33:12.921: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/update/
00:33:12.972: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/update/gold/
00:33:13.023: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/update/gold/firmware.der
00:33:13.086: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/update/gold/info.plist
00:33:13.143: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/update/gold/profile.bin
00:33:13.194: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/update/main/
00:33:14.135: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/update/main/firmware.der
00:33:14.187: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/update/main/info.plist
00:33:14.249: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/update/main/profile.bin
00:33:14.310: amai: _VinylBBFWReaderCB: Vinyl copied 41584afd3e447c10db18477031f538daeed0c7d3/recovery/
00:33:14.361: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/
00:33:14.414: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/upd
                     ate/
00:33:14.465: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/upd
                     ate/gold/
00:33:14.518: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/upd
                     ate/gold/firmware.der
00:33:14.569: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/upd
                     ate/gold/info.plist
00:33:14.620: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/upd
                     ate/gold/profile.bin
00:33:14.671: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/upda
                     te/main/
00:33:15.223: /
00:33:15.774: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/upd
                     ate/main/firmware.der
00:33:15.825: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/upd
                     ate/main/info.plist
00:33:15.875: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/upd
                     ate/main/profile.bin
00:33:15.926: amai: _VinylBBFWReaderCB: Vinyl copied d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/reco
                     very/
00:33:15.977: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/
00:33:16.028: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/upd
                     ate/
00:33:16.078: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/upd
                     ate/gold/
00:33:16.128: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/upd
                     ate/gold/firmware.der
00:33:16.179: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/upd
                     ate/gold/info.plist
00:33:16.230: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/upd
                     ate/gold/profile.bin
00:33:16.281: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/upd
                     ate/main/
00:33:17.334: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/upd
                     ate/main/firmware.der
00:33:17.384: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/upd
                     ate/main/info.plist
00:33:17.434: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/upd
                     ate/main/profile.bin
00:33:17.486: amai: _VinylBBFWReaderCB: Vinyl copied e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/rec
                     overy/
00:33:17.716: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/
00:33:17.779: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/update
                     /
00:33:17.830: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/updat
                     e/gold/
00:33:17.881: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/update
                     /gold/firmware.der
00:33:17.932: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/updat
                     e/gold/info.plist
00:33:18.036: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/updat
                     e/gold/profile.bin
00:33:18.087: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/updat
                     e/main/
00:33:18.138: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/update
                     /main/firmware.der
00:33:18.189: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/update
                     /main/info.plist
00:33:18.240: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/updat
                     e/main/profile.bin
00:33:18.291: amai: _VinylBBFWReaderCB: Vinyl copied e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/recove
                     ry/
00:33:18.342: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/
00:33:18.392: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/
00:33:18.443: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/gold/
00:33:18.494: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/gold/firmware.der
00:33:18.545: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/gold/info.plist
00:33:18.595: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/gold/profile.bin
00:33:18.647: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/main/
00:33:18.698: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/main/firmware.der
00:33:18.749: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/main/info.plist
00:33:18.800: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/main/profile.bin
00:33:18.861: amai: _VinylBBFWReaderCB: Vinyl copied f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/recov
                     ery/
00:33:18.971: amai: _VinylStitchInternal: 0
00:33:19.029: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/update/main/profile.bin
00:33:19.098: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/up
                     date/gold/profile.bin
00:33:19.150: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/up
                     date/
00:33:19.200: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/re
                     covery/
00:33:19.251: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/up
                     date/main/firmware.der
00:33:19.303: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upd
                     ate/main/profile.bin
00:33:19.354: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/up
                     date/gold/profile.bin
00:33:24.913: amai: BbfwWriterAddFile: Added bbfw file : RFFW.elf
00:33:24.963: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/update/main/info.plist
00:33:26.016: amai: BbfwWriterAddFile: Added bbfw file : upc.elf
00:33:26.088: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/up
                     date/
00:33:26.163: amai: BbfwWriterAddFile: Added bbfw file : ant_cfg_data.elf
00:33:26.213: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/up
                     date/main/profile.bin
00:33:26.265: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/u
                     pdate/main/ticket.der
00:33:26.316: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/
00:33:26.367: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upd
                     ate/main/
00:33:26.418: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/up
                     date/main/profile.bin
00:33:26.469: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/upd
                     ate/gold/firmware.der
00:33:26.520: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/update/gold/profile.bin
00:33:26.571: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/update/gold/info.plist
00:33:26.622: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/u
                     pdate/gold/ticket.der
00:33:26.673: amai: BbfwWriterAddFile: Added bbfw file : TPCU.elf
00:33:28.731: amai: BbfwWriterAddFile: Added bbfw file : SYS_SW.elf
00:33:28.805: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/up
                     date/main/info.plist
00:33:28.890: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/re
                     covery/
00:33:28.957: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/upd
                     ate/
00:33:29.008: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/u
                     pdate/main/
00:33:29.060: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/up
                     date/gold/
00:33:29.111: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/gold/firmware.der
00:33:29.162: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/
00:33:29.213: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/up
                     date/gold/info.plist
00:33:29.266: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/up
                     date/main/info.plist
00:33:29.317: amai: BbfwWriterAddFile: Added bbfw file : bbticket.der
00:33:29.368: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/upd
                     ate/gold/profile.bin
00:33:29.419: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/up
                     date/main/
00:33:29.471: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/
00:33:29.522: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/up
                     date/gold/firmware.der
00:33:29.574: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/upd
                     ate/main/
00:33:29.624: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/upd
                     ate/main/firmware.der
00:33:29.676: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/u
                     pdate/gold/
00:33:29.727: amai: BbfwWriterAddFile: Added bbfw file : legacy_rat_fw.elf
00:33:29.778: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upd
                     ate/gold/info.plist
00:33:29.830: amai: BbfwWriterAddFile: Added bbfw file : restorepsi2.bin
00:33:29.880: amai: BbfwWriterAddFile: Added bbfw file : psi_ram2.bin
00:33:29.931: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/update/gold/firmware.der
00:33:29.984: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/reco
                     very/
00:33:30.036: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/upd
                     ate/main/profile.bin
00:33:30.087: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/update/main/firmware.der
00:33:30.137: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upd
                     ate/
00:33:30.189: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/update/main/
00:33:30.240: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/up
                     date/gold/
00:33:30.292: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/up
                     date/main/firmware.der
00:33:30.343: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/upd
                     ate/gold/
00:33:30.394: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/u
                     pdate/gold/firmware.der
00:33:30.445: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/u
                     pdate/main/info.plist
00:33:30.497: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/rec
                     overy/
00:33:30.547: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/upd
                     ate/main/info.plist
00:33:30.597: amai: BbfwWriterAddFile: Added bbfw file : d5c44aafd2cc603075640cec160c8af0446078c3a855bc8c9fd9f2cfb0064edc/up
                     date/main/firmware.der
00:33:30.650: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/u
                     pdate/gold/info.plist
00:33:30.701: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/update/
00:33:30.752: amai: BbfwWriterAddFile: Added bbfw file : bbcfg.bin
00:33:30.803: amai: BbfwWriterAddFile: Added bbfw file : ebl.bin
00:33:30.855: amai: BbfwWriterAddFile: Added bbfw file : custpack.elf
00:33:30.906: amai: BbfwWriterAddFile: Added bbfw file : e12a06d7c9acc19666323bae1444e3fe8c0210406185c69dcd08dea70662b762/
00:33:30.957: amai: BbfwWriterAddFile: Added bbfw file : e1b1daf1539e54f1b5983fe2aa2c7908c1e780502bfd2a1059e7368ff3302a99/upd
                     ate/gold/info.plist
00:33:31.008: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/recovery/
00:33:31.058: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/update/gold/
00:33:31.110: amai: BbfwWriterAddFile: Added bbfw file : f345aaf50d4e7174442a7d911d98f3eb21cc36acf8d62ae748cd989346fb9bae/upda
                     te/gold/profile.bin
00:33:31.161: amai: BbfwWriterAddFile: Added bbfw file : 41584afd3e447c10db18477031f538daeed0c7d3/
00:33:53.280: amai: _AMAuthInstallBundleInstallPersonalizedEntry: entry "OS" does not require personalization; skipping it
00:34:14.865: Setting kAMRestoreOptionsiBootEANNuke.
00:34:14.916: AMDeviceCopyFDRPreflightOptions: Skipping FDR preflight
00:34:14.969: Successfully preflighted restore
00:34:15.019: Entering recovery mode
00:34:15.021:  Switching to recovery mode
00:34:18.578: Finished BootedOS Restore Phase: Successful
00:34:22.165: Looking up device with muxID:2
00:34:22.236: Muxed device disconnected with ECID: 0x1534A90C85802E
00:34:22.295: BootedOS mode device disconnected
00:34:22.347: Device removed when in state Restoring, moving device to transition state
00:34:22.429: Changing state from 'Restoring' to 'Transitioning'
00:34:22.455:  Waiting for the iDevice to reconnect after switch mode completed. The maximum waiting time is 10 minutes.
00:34:22.512: Creating timer to monitor transition
00:34:22.563: Creating a timer for 10 minutes
00:34:22.614: RSD device disconnected with ECID: 0x1534A90C85802E
00:34:22.666: Ignoring RSD disconnect event for non-RSD restorable device
00:34:22.716: Invalid remote service device ref.
00:34:22.766: Invalid ECID passed to make key with
00:34:22.817: Failed to create ecid key for RSD device
00:34:31.881: device connected (isDFU = 0), registryID 0x100000aa6
00:34:31.933: Recovery mode device connected with ECID: 0x1534A90C85802E
00:34:31.983: Found ECID: 0x1534A90C85802E
00:34:32.034: Found known device, nudging state machine.
00:34:32.085: Recovery mode device connected
00:34:32.136: Transitioning device returned, continuing restore.
00:34:32.186: Canceling timer
00:34:32.237: Changing state from 'Transitioning' to 'Restoring'
00:34:32.238:  switch mode succeeds, continue flashing
00:34:32.288: requested restore behavior: Erase
00:34:32.288:  Flash mode: Don't Retain User's Data While Flashing
00:34:32.339: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: searching for variant Erase (0 recovery)
00:34:32.391: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: AMAuthInstallBundleCopyBuildIdentityForVariant: Found variant: Cust
                     omer Erase Install (IPSW)
00:34:32.442: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:34:32.493: no override trust object found
00:34:32.543: requested restore behavior: Erase
00:34:32.544:  Flash mode: Don't Retain User's Data While Flashing
00:34:32.595: requested restore behavior: Erase
00:34:32.595:  Flash mode: Don't Retain User's Data While Flashing
00:34:32.646: Device will not use nonce slots
00:34:32.697: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536854449): {
00:34:32.749: 00:34:32.803: }
00:34:32.854: command device request for 'getenv anid' failed: 2008
00:34:32.923: No anid set, will not set anid in IM4R
00:34:32.973: requested restore behavior: Erase
00:34:32.973:  Flash mode: Don't Retain User's Data While Flashing
00:34:33.024: requested variant: Erase
00:34:33.075: no override trust object found
00:34:33.126: requested restore behavior: Erase
00:34:33.126:  Flash mode: Don't Retain User's Data While Flashing
00:34:33.177: requested restore behavior: Erase
00:34:33.177:  Flash mode: Don't Retain User's Data While Flashing
00:34:33.228: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:34:33.279: personalizing: <AMAuthInstall 0x7f9603c48680>{ap=(personalize=YES d421ap ecid=0x1534a90c85802e, chipid=0x8030, bo
                     ardid=0x6, secDom=1, isProduction=YES, EPRO=YES, isSecure=YES, ESEC=YES, img4=YES, demotionPolicy=, managedBa
                     aCert=NO, slowRollBaaCert=NO, dpoc=(null), nonce=0x9a4bb56d86043a5547611e7306861fa1aa056411a7fb17d1875a3c3be8
                     07baed, sepNonce=0x110a34edd61a868cd99b82e70f34b3d94e0c65eb), bp=(personalize=YES), UserAuth=NO, iTunes=YES
                     , server="https://gs.apple.com:443", locale=Zh_cn, version="libauthinstall-1033.0.6", platform=mac/19H15/x86_64}
00:34:33.374: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:34:33.429: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:34:33.480: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreLogo to Manifest to personalize later
00:34:33.532: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreDeviceTree to Manifest to personalize later
00:34:33.583: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreKernelCache to Manifest to personalize later
00:34:33.636: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreRamDisk to Manifest to personalize later
00:34:33.687: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBEC to Manifest to personalize later
00:34:33.738: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBSS to Manifest to personalize later
00:34:33.789: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting KernelCache to Manifest to personalize later
00:34:33.840: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftap to Manifest to personalize later
00:34:33.891: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfta to Manifest to personalize later
00:34:33.942: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftsp to Manifest to personalize later
00:34:33.994: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfts to Manifest to personalize later
00:34:34.045: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,SystemVolumeCanonicalMetadata to Manifest to person
                     alize later
00:34:34.096: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SystemVolume to Manifest to personalize later
00:34:34.147: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting OS to Manifest to personalize later
00:34:34.198: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RecoveryMode to Manifest to personalize later
00:34:34.249: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Liquid to Manifest to personalize later
00:34:34.302: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow0 to Manifest to personalize later
00:34:34.355: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AVE to Manifest to personalize later
00:34:34.453: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ANE to Manifest to personalize later
00:34:34.505: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,HapticAssets to Manifest to personalize later
00:34:34.556: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryPlugin to Manifest to personalize later
00:34:34.607: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreSEP to Manifest to personalize later
00:34:34.664: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ISP to Manifest to personalize later
00:34:34.717: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SEP to Manifest to personalize later
00:34:34.768: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBoot to Manifest to personalize later
00:34:34.819: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreTrustCache to Manifest to personalize later
00:34:34.870: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet1 to Manifest to personalize later
00:34:34.921: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting DeviceTree to Manifest to personalize later
00:34:34.972: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AudioCodecFirmware to Manifest to personalize later
00:34:35.022: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting PMP to Manifest to personalize later
00:34:35.073: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LeapHaptics to Manifest to personalize later
00:34:35.124: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting StaticTrustCache to Manifest to personalize later
00:34:35.175: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging0 to Manifest to personalize later
00:34:35.225: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LLB to Manifest to personalize later
00:34:35.277: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow1 to Manifest to personalize later
00:34:35.328: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryFull to Manifest to personalize later
00:34:35.379: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AppleLogo to Manifest to personalize later
00:34:35.430: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SIO to Manifest to personalize later
00:34:35.480: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging1 to Manifest to personalize later
00:34:35.532: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting GFX to Manifest to personalize later
00:34:35.583: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AOP to Manifest to personalize later
00:34:35.634: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet0 to Manifest to personalize later
00:34:35.685: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting WCHFirmwareUpdater to Manifest to personalize later
00:34:35.736: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Multitouch to Manifest to personalize later
00:34:35.787: amai: _AMAuthInstallBundleCreateServerRequestDictionary: ticketPath amai/apimg4ticket.der , withApTicket is False,  (!True
                     && ( True || False))
00:34:35.838: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreLogo"
00:34:35.889: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreDeviceTree"
00:34:35.939: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreKernelCache"
00:34:35.990: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreRamDisk"
00:34:36.042: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "OSRamdisk" not part of manifest, skipping
00:34:36.093: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBEC"
00:34:36.144: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBSS"
00:34:36.194: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "KernelCache"
00:34:36.246: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftap" entry
00:34:36.297: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfta" entry
00:34:36.348: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftsp" entry
00:34:36.399: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfts" entry
00:34:36.450: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,SystemVolumeCanonicalMetadata"
00:34:36.501: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolumeCanonicalMetadata" not part of manife
                     st, skipping
00:34:36.553: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "BaseSystemVolume" not part of manifest, skipping
00:34:36.604: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,BaseSystemVolume" not part of manifest, skipping
00:34:36.654: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SystemVolume"
00:34:36.705: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolume" not part of manifest, skipping
00:34:36.756: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Ap,BaseSystemTrustCache" not part of manifest, skippin
                     g
00:34:36.808: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Diags" not part of manifest, skipping
00:34:36.858: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "CFELoader" not part of manifest, skipping
00:34:36.909: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "RBM" not part of manifest, skipping
00:34:36.960: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PHLEET" not part of manifest, skipping
00:34:37.011: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PERTOS" not part of manifest, skipping
00:34:37.062: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PEHammer" not part of manifest, skipping
00:34:37.114: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Alamo" not part of manifest, skipping
00:34:37.164: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "OS" entry
00:34:37.215: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RecoveryMode"
00:34:37.266: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Liquid"
00:34:37.344: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow0"
00:34:37.396: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AVE"
00:34:37.447: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ANE"
00:34:37.498: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,HapticAssets"
00:34:37.550: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryPlugin"
00:34:37.600: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreSEP"
00:34:37.651: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ISP"
00:34:37.703: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SEP"
00:34:37.754: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBoot"
00:34:37.805: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreTrustCache"
00:34:37.856: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet1"
00:34:37.907: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "DeviceTree"
00:34:37.958: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AudioCodecFirmware"
00:34:38.009: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "PMP"
00:34:38.060: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LeapHaptics"
00:34:38.110: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "StaticTrustCache"
00:34:38.162: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging0"
00:34:38.213: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LLB"
00:34:38.264: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow1"
00:34:38.315: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryFull"
00:34:38.377: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AppleLogo"
00:34:38.478: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SIO"
00:34:38.529: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging1"
00:34:38.580: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "GFX"
00:34:38.632: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AOP"
00:34:38.683: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet0"
00:34:38.734: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "WCHFirmwareUpdater"
00:34:38.785: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Multitouch"
00:34:38.835: amai: AMSupportPlatformCreateBufferFromNativeFilePath: open failed: No such file or directory
00:34:38.887: amai: AMSupportPlatformCreateBufferFromNativeFilePath: /usr/local/standalone/firmware/device_map.plist
00:34:38.938: amai: AMAuthInstallApCopyDeviceEntryFromDeviceMap: Failed to read devicemap from file:///usr/local/standalone/firmwa
                     re/device_map.plist
00:34:38.989: amai: AMAuthInstallApImg4ServerRequestAddUIDMode: Could not check if UID mode is required.
00:34:39.040: amai: _AMAuthInstallBundleCreateServerRequestDictionary: nothing to be done
00:34:39.091: Setting kAMRestoreOptionsiBootEANNuke.
00:34:39.142: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536854449): {
00:34:39.193: 00:34:39.245: }
00:34:39.296: command device request for 'getenv ota-uuid' failed: 2008
00:34:39.346: Failed to copy env variable, error:21
00:34:39.398: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536870160): {
00:34:39.449: 00:34:39.500: }
00:34:39.551: error setting interface's alternate setting: 2009 (expected, not fatal).
00:34:41.630: iBoot build-version = iBoot-10151.140.19
00:34:41.680: iBoot build-style = RELEASE
00:34:41.732: <Recovery Mode Device 0x7f9603c682c0>: operation 4 progress -1
00:34:41.782: unable to open device_map.txt: No such file or directory
00:34:41.833: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:34:41.885: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:34:41.935: requested restore behavior: Erase
00:34:41.936:  Flash mode: Don't Retain User's Data While Flashing
00:34:41.987: requested restore behavior: Erase
00:34:41.987:  Flash mode: Don't Retain User's Data While Flashing
00:34:42.037: unable to open device_map.txt: No such file or directory
00:34:42.088: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:34:42.139: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:34:42.189: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536854449): {
00:34:42.242: 00:34:42.293: }
00:34:42.344: command device request for 'getenv radio-error' failed: 2008
00:34:42.394: radio-error not set
00:34:42.449: unable to open device_map.txt: No such file or directory
00:34:42.500: <Recovery Mode Device 0x7f9603c682c0>: production fused device
00:34:42.550: unable to open device_map.txt: No such file or directory
00:34:42.609: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:34:42.662: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:34:42.800: requested restore behavior: Erase
00:34:42.839:  Flash mode: Don't Retain User's Data While Flashing
00:34:42.918: requested restore behavior: Erase
00:34:42.918:  Flash mode: Don't Retain User's Data While Flashing
00:34:42.968: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536854449): {
00:34:43.020: 00:34:43.071: }
00:34:43.122: command device request for 'getenv boot-stage' failed: 2008
00:34:43.173: bootstrapping restore with iBEC
00:34:43.225: requested restore behavior: Erase
00:34:43.225:  Flash mode: Don't Retain User's Data While Flashing
00:34:43.276: Max file size is: 536870912
00:34:43.327: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/dfu/iBEC_iBEC.d421.REL
                     EASE.img4
00:34:43.327:  Sending iBEC
00:34:43.327:  The iDevice will switch to black screen recovery mode
00:34:43.379: <Recovery Mode Device 0x7f9603c682c0>: operation 31 progress -1
00:34:43.429: <Recovery Mode Device 0x7f9603c682c0>: Recovery mode succeeded
00:34:43.479: Finished Recovery Restore Phase: Successful
00:34:45.033: device disconnected (isDFU = 0), registryID 0x100000aa6
00:34:45.084: Found ECID: 0x1534A90C85802E
00:34:45.134: Recovery mode device disconnected with ECID: 0x1534A90C85802E
00:34:45.186: Recovery mode device disconnected
00:34:45.237: Device removed when in state Restoring, moving device to transition state
00:34:45.288: Changing state from 'Restoring' to 'Transitioning'
00:34:45.288:  Waiting for the iDevice to reconnect after switch mode completed. The maximum waiting time is 10 minutes.
00:34:45.339: Creating timer to monitor transition
00:34:45.390: Creating a timer for 10 minutes
00:34:46.972: device connected (isDFU = 0), registryID 0x100000ac7
00:34:47.023: Recovery mode device connected with ECID: 0x1534A90C85802E
00:34:47.100: Found ECID: 0x1534A90C85802E
00:34:47.158: Found known device, nudging state machine.
00:34:47.210: _AMRecoveryModeDeviceFinalize: 0x7f9603c682c0
00:34:47.262: Recovery mode device connected
00:34:47.313: Transitioning device returned, continuing restore.
00:34:47.363: Canceling timer
00:34:47.415: Changing state from 'Transitioning' to 'Restoring'
00:34:47.416:  switch mode succeeds, continue flashing
00:34:47.467: requested restore behavior: Erase
00:34:47.467:  Flash mode: Don't Retain User's Data While Flashing
00:34:47.518: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: searching for variant Erase (0 recovery)
00:34:47.568: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: AMAuthInstallBundleCopyBuildIdentityForVariant: Found variant: Cus
                     tomer Erase Install (IPSW)
00:34:47.619: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:34:47.670: no override trust object found
00:34:47.722: requested restore behavior: Erase
00:34:47.722:  Flash mode: Don't Retain User's Data While Flashing
00:34:47.773: requested restore behavior: Erase
00:34:47.773:  Flash mode: Don't Retain User's Data While Flashing
00:34:47.824: Device will not use nonce slots
00:34:47.875: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536854449): {
00:34:47.926: 00:34:47.977: }
00:34:48.030: command device request for 'getenv anid' failed: 2008
00:34:48.083: No anid set, will not set anid in IM4R
00:34:48.133: requested restore behavior: Erase
00:34:48.133:  Flash mode: Don't Retain User's Data While Flashing
00:34:48.184: requested variant: Erase
00:34:48.235: no override trust object found
00:34:48.286: requested restore behavior: Erase
00:34:48.286:  Flash mode: Don't Retain User's Data While Flashing
00:34:48.337: requested restore behavior: Erase
00:34:48.337:  Flash mode: Don't Retain User's Data While Flashing
00:34:48.388: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:34:48.440: personalizing: <AMAuthInstall 0x7f9603c83dd0>{ap=(personalize=YES d421ap ecid=0x1534a90c85802e, chipid=0x8030, bo
                     ardid=0x6, secDom=1, isProduction=YES, EPRO=YES, isSecure=YES, ESEC=YES, img4=YES, demotionPolicy=, managedBa
                     aCert=NO, slowRollBaaCert=NO, dpoc=(null), nonce=0x9a4bb56d86043a5547611e7306861fa1aa056411a7fb17d1875a3c3be8
                     07baed, sepNonce=0x110a34edd61a868cd99b82e70f34b3d94e0c65eb), bp=(personalize=YES), UserAuth=NO, iTunes=YES
                     , server="https://gs.apple.com:443", locale=Zh_cn, version="libauthinstall-1033.0.6", platform=mac/19H15/x86_64}
00:34:48.490: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:34:48.541: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:34:48.592: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreLogo to Manifest to personalize later
00:34:48.642: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreDeviceTree to Manifest to personalize later
00:34:48.693: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreKernelCache to Manifest to personalize later
00:34:48.743: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreRamDisk to Manifest to personalize later
00:34:48.795: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBEC to Manifest to personalize later
00:34:48.848: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBSS to Manifest to personalize later
00:34:48.900: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting KernelCache to Manifest to personalize later
00:34:48.950: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftap to Manifest to personalize later
00:34:49.001: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfta to Manifest to personalize later
00:34:49.051: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftsp to Manifest to personalize later
00:34:49.102: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfts to Manifest to personalize later
00:34:49.153: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,SystemVolumeCanonicalMetadata to Manifest to persona
                     lize later
00:34:49.204: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SystemVolume to Manifest to personalize later
00:34:49.254: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting OS to Manifest to personalize later
00:34:49.305: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RecoveryMode to Manifest to personalize later
00:34:49.355: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Liquid to Manifest to personalize later
00:34:49.406: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow0 to Manifest to personalize later
00:34:49.458: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AVE to Manifest to personalize later
00:34:49.541: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ANE to Manifest to personalize later
00:34:49.592: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,HapticAssets to Manifest to personalize later
00:34:49.677: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryPlugin to Manifest to personalize later
00:34:49.728: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreSEP to Manifest to personalize later
00:34:49.779: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ISP to Manifest to personalize later
00:34:49.833: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SEP to Manifest to personalize later
00:34:49.885: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBoot to Manifest to personalize later
00:34:49.936: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreTrustCache to Manifest to personalize later
00:34:49.987: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet1 to Manifest to personalize later
00:34:50.038: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting DeviceTree to Manifest to personalize later
00:34:50.090: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AudioCodecFirmware to Manifest to personalize later
00:34:50.141: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting PMP to Manifest to personalize later
00:34:50.192: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LeapHaptics to Manifest to personalize later
00:34:50.242: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting StaticTrustCache to Manifest to personalize later
00:34:50.293: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging0 to Manifest to personalize later
00:34:50.344: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LLB to Manifest to personalize later
00:34:50.395: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow1 to Manifest to personalize later
00:34:50.446: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryFull to Manifest to personalize later
00:34:50.499: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AppleLogo to Manifest to personalize later
00:34:50.550: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SIO to Manifest to personalize later
00:34:50.601: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging1 to Manifest to personalize later
00:34:50.653: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting GFX to Manifest to personalize later
00:34:50.704: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AOP to Manifest to personalize later
00:34:50.754: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet0 to Manifest to personalize later
00:34:50.805: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting WCHFirmwareUpdater to Manifest to personalize later
00:34:50.857: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Multitouch to Manifest to personalize later
00:34:50.907: amai: _AMAuthInstallBundleCreateServerRequestDictionary: ticketPath amai/apimg4ticket.der , withApTicket is False,  (!True
                     && ( True || False))
00:34:50.958: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreLogo"
00:34:51.008: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreDeviceTree"
00:34:51.060: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreKernelCache"
00:34:51.111: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreRamDisk"
00:34:51.162: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "OSRamdisk" not part of manifest, skipping
00:34:51.213: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBEC"
00:34:51.266: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBSS"
00:34:51.317: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "KernelCache"
00:34:51.368: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftap" entry
00:34:51.420: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfta" entry
00:34:51.471: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftsp" entry
00:34:51.521: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfts" entry
00:34:51.572: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,SystemVolumeCanonicalMetadata"
00:34:51.623: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolumeCanonicalMetadata" not part of manife
                     st, skipping
00:34:51.674: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "BaseSystemVolume" not part of manifest, skipping
00:34:51.725: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,BaseSystemVolume" not part of manifest, skipping
00:34:51.776: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SystemVolume"
00:34:51.827: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolume" not part of manifest, skipping
00:34:51.878: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Ap,BaseSystemTrustCache" not part of manifest, skipping
00:34:51.930: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Diags" not part of manifest, skipping
00:34:51.980: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "CFELoader" not part of manifest, skipping
00:34:52.033: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "RBM" not part of manifest, skipping
00:34:52.084: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PHLEET" not part of manifest, skipping
00:34:52.135: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PERTOS" not part of manifest, skipping
00:34:52.186: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PEHammer" not part of manifest, skipping
00:34:52.236: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Alamo" not part of manifest, skipping
00:34:52.287: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "OS" entry
00:34:52.390: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RecoveryMode"
00:34:52.441: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Liquid"
00:34:52.492: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow0"
00:34:52.543: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AVE"
00:34:52.593: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ANE"
00:34:52.644: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,HapticAssets"
00:34:52.695: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryPlugin"
00:34:52.746: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreSEP"
00:34:52.798: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ISP"
00:34:52.851: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SEP"
00:34:52.902: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBoot"
00:34:52.954: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreTrustCache"
00:34:53.005: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet1"
00:34:53.056: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "DeviceTree"
00:34:53.106: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AudioCodecFirmware"
00:34:53.158: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "PMP"
00:34:53.208: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LeapHaptics"
00:34:53.260: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "StaticTrustCache"
00:34:53.310: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging0"
00:34:53.361: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LLB"
00:34:53.411: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow1"
00:34:53.462: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryFull"
00:34:53.514: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AppleLogo"
00:34:53.565: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SIO"
00:34:53.618: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging1"
00:34:53.669: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "GFX"
00:34:53.721: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AOP"
00:34:53.771: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet0"
00:34:53.823: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "WCHFirmwareUpdater"
00:34:53.874: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Multitouch"
00:34:53.926: amai: AMSupportPlatformCreateBufferFromNativeFilePath: open failed: No such file or directory
00:34:53.976: amai: AMSupportPlatformCreateBufferFromNativeFilePath: /usr/local/standalone/firmware/device_map.plist
00:34:54.027: amai: AMAuthInstallApCopyDeviceEntryFromDeviceMap: Failed to read devicemap from file:///usr/local/standalone/firmwar
                     e/device_map.plist
00:34:54.078: amai: AMAuthInstallApImg4ServerRequestAddUIDMode: Could not check if UID mode is required.
00:34:54.130: amai: _AMAuthInstallBundleCreateServerRequestDictionary: nothing to be done
00:34:54.181: Setting kAMRestoreOptionsiBootEANNuke.
00:34:54.232: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536854449): {
00:34:54.283: 00:34:54.334: }
00:34:54.387: command device request for 'getenv ota-uuid' failed: 2008
00:34:54.438: Failed to copy env variable, error:21
00:34:54.489: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536870195): {
00:34:54.540: 00:34:54.590: }
00:34:54.641: error setting interface's alternate setting: 2001 (expected, not fatal).
00:34:54.691: iBoot build-version = iBoot-11881.80.57
00:34:54.741: iBoot build-style = RELEASE
00:34:54.792: <Recovery Mode Device 0x7f9603d31d50>: operation 4 progress -1
00:34:54.848: unable to open device_map.txt: No such file or directory
00:34:54.927: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:34:54.978: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:34:55.029: requested restore behavior: Erase
00:34:55.029:  Flash mode: Don't Retain User's Data While Flashing
00:34:55.080: requested restore behavior: Erase
00:34:55.080:  Flash mode: Don't Retain User's Data While Flashing
00:34:55.137: unable to open device_map.txt: No such file or directory
00:34:55.201: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:34:55.253: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:34:55.304: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536854449): {
00:34:55.355: 00:34:55.407: }
00:34:55.458: command device request for 'getenv radio-error' failed: 2008
00:34:55.509: radio-error not set
00:34:55.559: unable to open device_map.txt: No such file or directory
00:34:55.611: <Recovery Mode Device 0x7f9603d31d50>: production fused device
00:34:55.661: unable to open device_map.txt: No such file or directory
00:34:55.712: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:34:55.763: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:34:55.814: requested restore behavior: Erase
00:34:55.814:  Flash mode: Don't Retain User's Data While Flashing
00:34:55.865: requested restore behavior: Erase
00:34:55.865:  Flash mode: Don't Retain User's Data While Flashing
00:34:55.916: unable to open device_map.txt: No such file or directory
00:34:55.968: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:34:56.020: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:34:56.071: requested restore behavior: Erase
00:34:56.073:  Flash mode: Don't Retain User's Data While Flashing
00:34:56.123: requested restore behavior: Erase
00:34:56.123:  Flash mode: Don't Retain User's Data While Flashing
00:34:56.174: requested restore behavior: Erase
00:34:56.174:  Flash mode: Don't Retain User's Data While Flashing
00:34:56.225: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536854449): {
00:34:56.276: 00:34:56.327: }
00:34:56.377: command device request for 'getenv boot-stage' failed: 2008
00:34:56.430: requested restore behavior: Erase
00:34:56.430:  Flash mode: Don't Retain User's Data While Flashing
00:34:56.481: <Recovery Mode Device 0x7f9603d31d50>: operation 43 progress -1
00:34:56.533: requested restore behavior: Erase
00:34:56.533:  Flash mode: Don't Retain User's Data While Flashing
00:34:56.583: Max file size is: 536870912
00:34:56.634: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/all_flash/RestoreLogo_ap
                     plelogo@3x~iphone.img4
00:34:56.634:  Sending Restore Logo
00:34:56.685: No additional boot images found
00:34:56.737: unable to open device_map.txt: No such file or directory
00:34:56.790: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:34:56.840: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:34:56.892: <Recovery Mode Device 0x7f9603d31d50>: operation 8 progress -1
00:34:56.943: unable to open device_map.txt: No such file or directory
00:34:56.993: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:34:57.044: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:34:57.095: No readable value found in kAMRestoreOptionsRestoreNVRAMVariables
00:34:57.145: Sending RestoreTrustCache to device. (1 of 9)
00:34:57.196: Max file size is: 536870912
00:34:57.247: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/RestoreTrustCache_044-
                     95786-001.dmg.img4
00:34:57.247:  Sending Restore Trust Cache
00:34:57.299: Sending AVE to device. (2 of 9)
00:34:57.349: Max file size is: 536870912
00:34:57.400: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/ave/AVE_AppleAVE2FW_
                     H12.img4
00:34:57.450: Sending SIO to device. (3 of 9)
00:34:57.502: Max file size is: 536870912
00:34:57.555: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/SIO_SmartIOFirmware_AS
                     Cv2.img4
00:34:57.607: Sending AOP to device. (4 of 9)
00:34:57.658: Max file size is: 536870912
00:34:57.710: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/AOP/AOP_aopfw-iphone1
                     2aop.RELEASE.img4
00:34:57.760: Sending WCHFirmwareUpdater to device. (5 of 9)
00:34:57.810: Max file size is: 536870912
00:34:57.861: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/WirelessPower/WCHFirm
                     wareUpdater_WirelessPower.iphone12.img4
00:34:57.912: Sending ANE to device. (6 of 9)
00:34:57.963: Max file size is: 536870912
00:34:58.015: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/ane/ANE_h12_ane_fw_me
                     tis.img4
00:34:58.066: Sending ISP to device. (7 of 9)
00:34:58.117: Max file size is: 536870912
00:34:58.167: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/isp_bni/ISP_adc-zelus-d4
                     x.img4
00:34:58.218: Sending GFX to device. (8 of 9)
00:34:58.269: Max file size is: 536870912
00:34:58.323: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/agx/GFX_armfw_g12p.im
                     g4
00:34:58.374: Sending PMP to device. (9 of 9)
00:34:58.425: Max file size is: 536870912
00:34:58.475: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/pmp/PMP_t8030pmp.img
                     4
00:34:58.525: <Recovery Mode Device 0x7f9603d31d50>: operation 5 progress -1
00:34:58.577: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/RestoreRamDisk_044-95786-001.im
                     g4
00:34:58.577:  Sending Restore Ram Disk
00:35:01.130: unable to open device_map.txt: No such file or directory
00:35:01.181: found device map entry for 0x00008030 0x00000006 0x00000001. boardConfig=d421ap platform=t8030
00:35:01.231: _AMRestoreCopyDeviceMapPlistEntryForHardware: firmwareDirectory not in options
00:35:01.281: _AMRUSBDeviceSendDeviceRequestTO_block_invoke: AMRUSBDevice error (-536854449): {
00:35:01.332: 00:35:01.451: }
00:35:01.503: command device request for 'getenv ramdisk-delay' failed: 2008
00:35:04.557: <Recovery Mode Device 0x7f9603d31d50>: operation 6 progress -1
00:35:04.610: Max file size is: 536870912
00:35:04.662: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/all_flash/RestoreDeviceT
                     ree_DeviceTree.d421ap.img4
00:35:04.662:  Sending Restore Device Tree
00:35:05.713: <Recovery Mode Device 0x7f9603d31d50>: operation 6 progress -1
00:35:05.765: Max file size is: 536870912
00:35:05.818: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/Firmware/all_flash/RestoreSEP_sep
                     -firmware.d421.RELEASE.img4
00:35:06.395: <Recovery Mode Device 0x7f9603d31d50>: operation 7 progress -1
00:35:06.446: Max file size is: 536870912
00:35:06.497: sending file: /tmp/PersonalizedBundle_636BAECC-8063-45C0-8368-4CE5F33FD2E4/RestoreKernelCache_kernelcache.re
                     lease.img4
00:35:06.497:  Sending Restore Kernel Cache
00:35:08.055: <Recovery Mode Device 0x7f9603d31d50>: operation 9 progress -1
00:35:08.152: <Recovery Mode Device 0x7f9603d31d50>: Recovery mode succeeded
00:35:08.203: Finished Recovery Restore Phase: Successful
00:35:08.204:  Starting micro-iOS operating system in RAM for restore.
00:35:08.204:  The iDevice will switch to Normal mode
00:35:09.295: device disconnected (isDFU = 0), registryID 0x100000ac7
00:35:09.369: Found ECID: 0x1534A90C85802E
00:35:09.439: Recovery mode device disconnected with ECID: 0x1534A90C85802E
00:35:09.490: Recovery mode device disconnected
00:35:09.541: Device removed when in state Restoring, moving device to transition state
00:35:09.593: Changing state from 'Restoring' to 'Transitioning'
00:35:09.593:  Waiting for the iDevice to reconnect after switch mode completed. The maximum waiting time is 10 minutes.
00:35:09.644: Creating timer to monitor transition
00:35:09.704: Creating a timer for 10 minutes
00:35:23.321: Mux version 3 event happened
00:35:23.388: IPv6 @ locationID=0x26400000: no NCM interfaces found
00:35:23.439: sock   8: connected to  [usbmux_3]:62078
00:35:23.490: connected to service com.apple.mobile.restored
00:35:23.541: using protocol version 15
00:35:23.592: supports value queries: 1
00:35:23.678: sock   8: closed
00:35:23.759: Muxed mode device connected with ECID: 0x1534A90C85802E
00:35:23.809: Found known device
00:35:23.872: _AMRecoveryModeDeviceFinalize: 0x7f9603d31d50
00:35:23.923: RestoreOS mode device connected
00:35:23.923:  Succeed to connect the micro-iOS operating system in RAM for restore.
00:35:23.980: Transitioning device returned, continuing restore.
00:35:24.063: Canceling timer
00:35:24.114: Changing state from 'Transitioning' to 'Debounce'
00:35:24.165: Creating timer to wait for USB debounce
00:35:24.217: Creating a timer for 2 seconds
00:35:25.268: Device still present after debounce timer, continuing restore
00:35:25.320: Changing state from 'Debounce' to 'Restoring'
00:35:25.371: requested restore behavior: Erase
00:35:25.371:  Flash mode: Don't Retain User's Data While Flashing
00:35:25.422: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: searching for variant Erase (0 recovery)
00:35:25.474: amai: AMAuthInstallBundleCopyBuildIdentityForVariant: AMAuthInstallBundleCopyBuildIdentityForVariant: Found variant: Cus
                     tomer Erase Install (IPSW)
00:35:25.524: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:35:25.577: no override trust object found
00:35:25.636: requested restore behavior: Erase
00:35:25.636:  Flash mode: Don't Retain User's Data While Flashing
00:35:25.686: amai: AMAuthInstallBasebandSetParametersWithUpdaterOutput: baseband updater output: {
00:35:25.738:     CertID = 524245983;
00:35:25.789:     ChipID = 104;
00:35:25.864: 00:35:25.925: 00:35:25.986:     VendorID = 2;
00:35:26.065: }
00:35:26.139: amai: AMAuthInstallBasebandSetParametersWithUpdaterOutput: manifest dict not found
00:35:26.207: amai: _AMAuthInstallBasebandCheckForParameterChange: bbParameters is now non-NULL
00:35:26.266: <Restore Device 0x7f9603d65960>: operation 45 progress -1
00:35:26.317: requested restore behavior: Erase
00:35:26.319:  Flash mode: Don't Retain User's Data While Flashing
00:35:26.370: requested variant: Erase
00:35:26.421: no override trust object found
00:35:26.471: requested restore behavior: Erase
00:35:26.471:  Flash mode: Don't Retain User's Data While Flashing
00:35:26.522: requested restore behavior: Erase
00:35:26.523:  Flash mode: Don't Retain User's Data While Flashing
00:35:26.573: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:35:26.624: personalizing: <AMAuthInstall 0x7f9603c43240>{ap=(personalize=YES d421ap ecid=0x1534a90c85802e, chipid=0x8030, bo
                     ardid=0x6, secDom=1, isProduction=YES, EPRO=YES, isSecure=YES, ESEC=YES, img4=YES, demotionPolicy=, managedBa
                     aCert=NO, slowRollBaaCert=NO, dpoc=(null)), bp=(personalize=YES, snum=0x1258e37c46f782f200000000, chipid=0x68, c
                     ertid=0x1f3f5bdf, nonce=0x9380a7826a99e2107212bcfba00e1a6fb6c02ed4), UserAuth=NO, iTunes=YES, server="https://g
                     s.apple.com:443", locale=Zh_cn, version="libauthinstall-1033.0.6", platform=mac/19H15/x86_64}
00:35:26.772: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:35:26.822: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:35:26.873: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreLogo to Manifest to personalize later
00:35:26.924: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreDeviceTree to Manifest to personalize later
00:35:26.975: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreKernelCache to Manifest to personalize later
00:35:27.025: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreRamDisk to Manifest to personalize later
00:35:27.078: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBEC to Manifest to personalize later
00:35:27.130: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBSS to Manifest to personalize later
00:35:27.202: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting KernelCache to Manifest to personalize later
00:35:27.253: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftap to Manifest to personalize later
00:35:27.303: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfta to Manifest to personalize later
00:35:27.354: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftsp to Manifest to personalize later
00:35:27.404: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfts to Manifest to personalize later
00:35:27.456: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,SystemVolumeCanonicalMetadata to Manifest to person
                     alize later
00:35:27.507: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SystemVolume to Manifest to personalize later
00:35:27.559: amai: AMAuthInstallBasebandCreateMeasurements: Using set ChipID 0x00000068 to measure
00:35:27.559:  Requesting baseband SHSH via network
00:35:27.609: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA384 to hash PSI-Version
00:35:27.662: amai: AMAuthInstallRembrandtMeasureBootPSI: PSI-Version: version=0x98b1392
00:35:27.713: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA384 to hash RestorePSI-Version
00:35:27.764: amai: AMAuthInstallRembrandtMeasureBootPSI: RestorePSI-Version: version=0x98b1393
00:35:27.815: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA256 to hash PSI-Version
00:35:27.866: amai: AMAuthInstallRembrandtMeasureBootPSI: PSI-Version: version=0x98b1392
00:35:27.917: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA256 to hash RestorePSI-Version
00:35:27.968: amai: AMAuthInstallRembrandtMeasureBootPSI: RestorePSI-Version: version=0x98b1393
00:35:28.018: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 776 bytes]
00:35:28.069: amai: : 30 00 00 00 10 00 00 00 04 59 43 5a a7 dc 49 30
00:35:28.120: amai: : 0c 62 66 c5 0f c5 ed fa cf f0 18 08 c5 64 02 88
00:35:28.171: amai: : 58 b5 26 c6 6d 97 1a 77 00 09 76 29 3b 16 25 2f
00:35:28.222: amai: : bd 94 96 8c 0c b9 b7 f9 bf 9e 36 9e bc 1f 6b 2c
00:35:28.274: amai: : 0a 1d 9f 31 0b bf 3b b5 11 18 e5 7d ff f6 74 3c
00:35:28.325: amai: : 54 3b 53 0d ae 19 e3 6b 0a 68 da 9c d9 c0 43 f0
00:35:28.376: amai: : 1d 55 62 e4 0e 85 10 d8 82 cf f4 88 29 a6 c0 19
00:35:28.426: amai: : a4 78 d9 7c 3c 39 5f 9b 2d 34 93 c2 57 50 a9 25
00:35:28.477: amai: : ee eb 83 15 9a 25 07 52 6e 29 11 7c 93 6c e8 e6
00:35:28.532: amai: : fa 86 1e b3 8d 43 02 8f 81 26 11 37 d8 fc 28 54
00:35:28.583: amai: : 2d 9e 5e 5f b4 6e c8 50 9c b3 76 02 a9 ff 42 d7
00:35:28.634: amai: : 4b e9 b3 d5 b4 23 b2 ef 76 f2 b2 bc 00 d4 62 00
00:35:28.687: amai: : 80 11 19 c8 9b 0e 38 85 9d c1 07 44 28 1d 5b b2
00:35:28.738: amai: : 22 8f 01 61 a1 c2 72 50 4f 2e e6 d0 9a 09 a9 f8
00:35:28.788: amai: : d8 31 14 95 55 9f b0 44 cd 9f 30 f7 50 a8 6b 6a
00:35:28.839: amai: : 43 95 b4 1d 11 85 a9 12 52 99 dd e6 b2 b4 9b d2
00:35:28.890: amai: : d6 f3 2a 5b 13 38 f0 51 f8 6d 48 d0 23 12 80 c7
00:35:28.941: amai: : 08 aa ea ae 79 0d 2f 44 34 bd 1e 02 9b 19 f6 31
00:35:28.992: amai: : bb fa 2e 87 1c 04 ce c9 0e 47 3a f1 05 10 ad 5d
00:35:29.043: amai: : 2d 05 60 01 89 cc 98 d0 fc df 69 59 e5 eb 0f f8
00:35:29.095: amai: : 49 5f a8 f4 7b f8 83 8c 64 d0 58 82 16 93 ba 50
00:35:29.148: amai: : f1 dc 7a 15 2e 98 00 8d 60 22 1f 54 a7 7a b2 a9
00:35:29.199: amai: : b1 51 d4 4b f7 a3 5c 40 47 24 e3 79 32 0b 47 53
00:35:29.250: amai: : c1 c3 aa 70 5a b4 d6 f7 f2 a6 31 a9 63 d1 a1 96
00:35:29.301: amai: : 6a 16 a6 6b 08 2a 8b 18 61 81 43 d1 a3 90 d2 33
00:35:29.351: amai: : 64 49 cb 89 f2 65 fc b3 93 2f 87 5b 1b 0a 86 da
00:35:29.402: amai: : da dc 4b df 0a bc e6 55 81 04 a9 d5 39 49 3f 43
00:35:29.454: amai: : d9 1f 4c 09 82 62 21 b3 0a bc fc 44 d7 a7 85 fc
00:35:29.505: amai: : 96 9c 8b 19 d5 62 8d 38 2e 0d 93 c0 bb f5 98 c7
00:35:29.557: amai: : f5 f9 55 23 07 21 ab dc 85 3d 18 8c 04 35 1a aa
00:35:29.607: amai: : 2e 41 1f cb b4 97 81 43 b4 2f 79 d8 d9 f6 c3 87
00:35:29.657: amai: : 7b 4c 9d 95 83 ef da 24 0d f6 dd e8 95 44 aa 39
00:35:29.709: amai: : 0d 79 c5 19 60 06 97 cc 8c 4d 8f 67 20 fa c4 87
00:35:29.759: amai: : 2f f8 b5 46 9b 0a 1b 4c 9c a3 91 d6 17 30 f4 a0
00:35:29.810: amai: : 0b 0e 72 43 95 df a7 0c 78 c5 9a 1b c9 85 db 5b
00:35:29.861: amai: : 49 56 59 bd 87 e3 12 44 82 06 e7 26 7a dd 41 14
00:35:29.917: amai: : 3e 37 89 ab 65 1d ee 0d 5b 22 6a 86 54 b1 96 18
00:35:29.968: amai: : 4e 7a b5 58 86 dd a3 8d 7b e5 6c 3b ce ed 17 d1
00:35:30.018: amai: : c6 96 95 1c ef 1c 5f 5b 03 15 13 75 39 03 1c 39
00:35:30.069: amai: : 12 d6 e9 e0 66 76 6e f9 35 c6 ee 74 9d a4 9d 69
00:35:30.120: amai: : 70 cd 16 6d 95 74 1d 64 bc fd 5c 65 91 a6 f0 ca
00:35:30.171: amai: : fa bb 9c c0 3a 07 a2 35 9a c2 69 75 a2 04 dd 01
00:35:30.221: amai: : 2f f2 23 ca 32 2b 66 1a f9 e3 5a 10 85 ef 64 5f
00:35:30.271: amai: : 8a d1 8e 07 2e 92 cc 7f ca a7 b4 03 b9 cc 46 9a
00:35:30.322: amai: : ae 39 92 f8 b4 64 2f d5 4c 0a 77 2e fa 98 c3 b3
00:35:30.372: amai: : d8 5c b7 aa 52 1a 3a ff d8 ba 3a a3 8b 70 2f e9
00:35:30.423: amai: : ab 55 44 39 a0 9b 7d 8d c7 c2 03 f3 b5 7a de 9c
00:35:30.474: amai: : be ec b3 ea f0 9b ac 65 58 81 1d 19 ff f8 96 1e
00:35:30.526: amai: : 35 71 6d 0f 04 f7 65 c3
00:35:30.577: amai: : -----------------------------------------------
00:35:30.628: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 1976 bytes]
00:35:30.678: amai: : 30 00 00 00 29 00 00 00 63 15 1e cc c4 41 0e fb
00:35:30.731: amai: : 28 ab 8b 25 cd bc e8 f1 ec 60 e4 8d 2a fa bc a7
00:35:30.782: amai: : cd b4 e4 c2 e1 95 be 16 e2 1b b5 db db 4d fd 27
00:35:30.833: amai: : 7e ba d0 ad 4c 98 54 10 0b 61 31 d6 d6 bd 8d 46
00:35:30.884: amai: : 71 c5 eb 40 d3 f3 3f 92 7d 15 a0 a7 f2 f1 28 57
00:35:30.934: amai: : 1e 0a 16 27 aa dc d9 67 24 f0 ed ba 57 de 1e a0
00:35:30.985: amai: : 61 a2 e8 4a fa a0 92 6e 31 7a 72 d5 df 0a fc 2c
00:35:31.035: amai: : ff 5e 12 05 d2 4c 00 f5 1b c8 ac a5 1f a7 90 fd
00:35:31.086: amai: : 1d ee e4 9e 34 d0 9b 21 f4 f8 ff 74 89 bd f8 fc
00:35:31.137: amai: : 74 cf 62 19 79 da 63 e9 87 90 a2 84 6d 67 bf 9b
00:35:31.188: amai: : 59 4d ac f7 2f 65 bb 3a 5a 08 8c b9 12 47 09 03
00:35:31.239: amai: : 50 14 4a 98 dd 73 a9 f6 d8 ea 00 46 36 7d 14 58
00:35:31.291: amai: : c2 d9 8e 73 af f1 80 aa 55 70 64 89 91 c5 fe c2
00:35:31.342: amai: : 84 8c 86 1b 55 5e b4 e4 23 7e db f1 32 34 a8 c0
00:35:31.392: amai: : d0 fb 1f 96 e3 44 94 27 75 45 4d c1 fb 06 41 b2
00:35:31.444: amai: : 9e a6 05 dc da f8 c2 cd ec f9 b2 b3 34 63 41 8d
00:35:31.494: amai: : 15 e3 b9 39 6b a4 38 ed 60 47 ff 42 72 ac 86 fb
00:35:31.546: amai: : 45 70 60 53 ab e4 09 c6 7c 4f 64 ad 22 d9 8d 95
00:35:31.597: amai: : f3 4a 42 bf 0b 70 4d b5 0d 53 f2 4f 63 f0 dd 6f
00:35:31.650: amai: : 24 90 09 f2 63 0e 57 da 83 7d eb e1 88 4f 42 75
00:35:31.702: amai: : 68 ea 39 5b 3b 1d d7 64 a0 4d 8a 02 35 39 d4 2c
00:35:31.752: amai: : 2b 7c 45 9b 1f b7 47 6b 02 87 e0 70 12 31 61 58
00:35:31.804: amai: : 51 9d 66 74 24 b5 48 f0 3b ee 83 81 10 d3 e8 04
00:35:31.855: amai: : 03 69 f0 39 e4 53 87 f9 a1 1c 0f b8 4d 9f 93 9d
00:35:31.906: amai: : 3b 36 fe b1 27 44 7b 9e 5d 0f 67 a4 97 86 cc 5c
00:35:31.958: amai: : 46 72 e8 34 0e 3f 14 a1 f8 f4 bb 63 d4 ca 6e 32
00:35:32.008: amai: : 85 5e 34 81 bf 8c 20 ca 2c 40 6d 15 81 1f b3 1c
00:35:32.059: amai: : b8 4e 86 45 2b 1e 00 a5 0e 2c 86 51 0f f3 bb ba
00:35:32.111: amai: : 28 10 be f2 00 e8 31 29 0a e2 9f b9 60 42 6f e1
00:35:32.162: amai: : 34 bb 5e e7 29 c6 35 25 ef c7 76 b4 ae 8e ec f6
00:35:32.213: amai: : c5 f1 41 a3 6e 8c 04 66 ae 34 d0 ba 56 fc 5f 9c
00:35:32.264: amai: : fc 48 1a b0 27 cf e4 6b f8 a1 51 cf 14 ae 6f 04
00:35:32.317: amai: : ee c8 8e 3c 74 d8 f5 2c 4e 8f 7d bc cc eb f3 5a
00:35:32.368: amai: : 8a c0 20 2f 7d 8a 61 d0 b3 c4 96 ba 87 ae d8 a0
00:35:32.419: amai: : 5a fc 0c 89 15 42 8c d8 4f 24 6f 5b e2 33 84 75
00:35:32.469: amai: : 42 bd 3d 82 e8 ad b1 28 29 d1 80 96 4c 8b 98 6c
00:35:32.519: amai: : d1 7f 1b 98 28 70 b0 05 7f 33 a1 81 c4 be 25 3e
00:35:32.653: amai: : e4 0c e9 e7 84 27 af 94 1b a7 14 32 23 4e 7b 60
00:35:32.704: amai: : 36 59 8e 62 4e 50 07 80 5b ec d6 3a 5c 95 92 4a
00:35:32.756: amai: : 6b 5b 09 be be 0b da 69 96 64 b9 48 c8 cf 9c 28
00:35:32.806: amai: : be fe 06 2e 6c a1 92 f5 1a d1 8d 67 30 66 2e ac
00:35:32.857: amai: : 6b 6b b5 a8 73 04 15 54 34 f1 81 2b 6e b1 c4 0d
00:35:32.908: amai: : 53 3b 7f 51 ed 2f 04 76 ee 52 5a 5c fc 6d 4a 11
00:35:32.959: amai: : e0 8c dc 20 99 6f fc ff 3e df 68 4e fc 90 f3 6b
00:35:33.010: amai: : 76 88 5d c1 b3 db 17 ca db 9a a1 9a 28 d2 e7 e4
00:35:33.061: amai: : fd 4b 36 7d 18 d7 49 5d d1 9d c2 12 1e 65 74 93
00:35:33.111: amai: : ca 8b 23 c6 12 6b a4 20 62 92 b3 4e 4a 93 62 fd
00:35:33.162: amai: : 9b ea 26 a4 e7 89 7b 4b b5 66 7f 23 d8 a5 59 1d
00:35:33.215: amai: : be 45 01 40 26 5b 2f f2 bb 63 97 ba c6 96 ef 44
00:35:33.267: amai: : 9c ea 1f d0 d3 ef 1b 68 f2 5d 2a 58 6f e5 d5 c3
00:35:33.318: amai: : 28 c3 eb 48 ce 83 75 1e b5 1d dd 6f cc 5f 6b 95
00:35:33.368: amai: : 06 b4 90 25 84 f0 38 65 5d 6b 29 2e be ae b2 41
00:35:33.418: amai: : 7c be 65 31 ba eb a3 d2 c2 4b 57 a5 1c 4c a2 bd
00:35:33.469: amai: : 4d 59 83 be db 3e 31 be 7f a8 e0 63 a5 b0 7e 8d
00:35:33.519: amai: : 5b 58 8b 7f 5b 3c 43 0a 15 d3 d5 7b 6e 4c 82 d5
00:35:33.571: amai: : bb 05 42 45 7f 0b a5 d8 78 d2 e5 a8 71 19 b7 03
00:35:33.621: amai: : d5 f5 b4 f9 a5 27 f3 21 7b ff eb 12 25 ae 92 e8
00:35:33.673: amai: : dd b2 e2 89 cb 06 99 03 40 35 29 e2 91 5a 39 66
00:35:33.724: amai: : 9a a1 6c 1b 35 92 6b 34 30 39 9d d5 b5 29 a9 ca
00:35:33.775: amai: : e8 b7 a6 a6 84 f9 18 5c 69 ca 2f 11 d1 37 ed 49
00:35:33.826: amai: : e8 7f cc a4 c8 51 72 a8 45 63 ab 86 1f ed 36 e6
00:35:33.876: amai: : 99 76 dd 4c 49 ce c1 32 8d be 31 dd 19 da b5 4c
00:35:33.928: amai: : 55 87 df 27 a0 4f bb e0 47 15 d6 6a 72 8d 4e 6e
00:35:33.979: amai: : cb f3 a7 1d 63 c6 90 5c 80 04 6c 64 53 6c a6 7a
00:35:34.030: amai: : 15 81 fc ae 62 83 76 e0 bb 5d 02 d1 36 82 d0 6f
00:35:34.081: amai: : 2b a6 03 4b 20 33 81 f3 72 7c 8d b7 8b 1c da 46
00:35:34.132: amai: : d9 8d ff f9 48 6a fb a3 29 98 31 18 00 f2 2a d2
00:35:34.185: amai: : 7e bc 89 cc da c9 2d 87 2d 03 d2 11 15 e7 be 00
00:35:34.235: amai: : 86 7c ce 00 49 5b 8a 01 f9 bb dc 41 22 d5 29 e4
00:35:34.286: amai: : 09 69 15 be 06 6d 12 6d ed 2e b5 46 50 1d 6f 37
00:35:34.346: amai: : bc c6 8a c8 70 b9 a8 66 c3 e2 c1 6d da 75 22 4a
00:35:34.397: amai: : 68 43 58 f9 8d 00 a8 4d 15 98 a1 e2 7b 95 86 f7
00:35:34.448: amai: : 3b 45 7c 3d 12 a4 be 97 08 c3 ab 86 18 ad 61 20
00:35:34.499: amai: : c0 27 bc 7e 10 bc 6b 0e 8a 08 5c 5f 19 35 4c 89
00:35:34.554: amai: : 03 02 1e f3 cb 4b 0c 51 49 ef f9 ca cf 24 55 8d
00:35:34.605: amai: : 10 52 ee c2 bf b1 53 28 50 c0 fd 97 e3 8f cc f1
00:35:34.655: amai: : f1 0e f3 fc 84 ae d6 3e a7 40 e6 9c fe 7e c5 17
00:35:34.706: amai: : a3 5b ba 54 0a e5 14 09 9e 0a 45 dc b5 fb 2f 37
00:35:34.757: amai: : af 05 0e 16 08 4e c8 d8 c9 35 2d 32 f6 8f 31 03
00:35:34.808: amai: : ca e4 9b e9 0b bd 95 8a 4e d5 bb 57 a6 ec f7 6b
00:35:34.858: amai: : e4 ce b8 26 35 f7 2b 98 dd 86 8d 7e 05 5e d8 74
00:35:34.910: amai: : 43 49 12 a0 c4 98 7a c1 6f 6d b9 72 b2 88 b0 e4
00:35:34.961: amai: : 96 73 8c b1 65 28 88 ad ed 36 72 7c 44 d0 5f 20
00:35:35.012: amai: : 46 6e 73 7a fb 3e 1a 1d a6 57 f1 46 ae ff 1a 09
00:35:35.272: amai: : ce ab b9 7a 98 17 61 08 7b f0 51 c5 03 f9 eb 0e
00:35:35.328: amai: : a3 31 89 b7 4e 2f b1 8e ec 96 7a 48 eb f9 91 a5
00:35:35.379: amai: : 26 ba 7e 66 86 ff 6b 6c e6 59 40 1d 0b e3 0d 14
00:35:35.431: amai: : 90 86 9f 8d a7 e4 fe 91 53 73 b5 00 91 8f 59 54
00:35:35.481: amai: : 56 e4 d2 0c 08 5f 0b 7b 4b 56 82 ea a6 f4 ef e9
00:35:35.531: amai: : 4c 7e e0 42 4b e6 05 80 a7 11 a2 ed 96 09 3a 38
00:35:35.582: amai: : 4c c4 a8 0d 29 9e fa 38 26 9a 8a c0 06 47 24 ee
00:35:35.638: amai: : 50 c4 c5 3d ff c5 34 89 dc df 55 65 f2 cd f7 e9
00:35:35.688: amai: : ff d3 6e 76 96 a9 33 96 14 12 58 6b d9 5d 8e 2d
00:35:35.739: amai: : 85 ba a6 6e 56 0f 38 b4 ba 3d 3d 77 eb 69 2e 34
00:35:35.790: amai: : e1 30 23 86 90 fb 83 2f d2 64 6c 99 17 4a 8b b7
00:35:35.880: amai: : fc 39 71 f0 26 0d 6a b0 53 7c 52 2d d0 e6 83 ac
00:35:35.930: amai: : eb 42 e3 79 6b 7a ea 9d 1b 75 f8 6e 31 80 41 08
00:35:35.981: amai: : c9 be d4 aa 86 4d 4c ad 97 b9 37 80 f0 fd dd 91
00:35:36.031: amai: : 6e 46 b8 8e 93 b0 8a ec aa 54 b9 94 04 ab b0 6c
00:35:36.082: amai: : d4 71 0f 82 c4 e4 7d 19 c1 73 44 08 fa 8f 7d 0e
00:35:36.138: amai: : 08 08 2f 6a 6c 58 41 68 a9 df af c8 88 9b 10 7f
00:35:36.198: amai: : 33 7f d6 28 28 c8 79 7f a2 c8 40 13 c3 78 e5 a4
00:35:36.248: amai: : 20 75 7b 33 f8 a3 53 e1 19 93 4a 01 45 56 68 09
00:35:36.299: amai: : 1e 62 8e 7c f4 ee 9a 8d 99 ed 83 91 84 d3 77 d4
00:35:36.350: amai: : ed 05 a4 2b 81 d0 8b 96 98 b8 14 4f db a9 12 ed
00:35:36.404: amai: : 95 45 c0 06 f0 53 59 49 15 43 c2 6f 54 86 7a 2a
00:35:36.455: amai: : 9e 3c 1a 4c 34 46 70 97 19 8b fd 40 ca fe 5c fb
00:35:36.505: amai: : 7b 28 ea 3b 20 09 a2 50 3d 2f d0 5b ff 57 94 17
00:35:36.555: amai: : 5f 59 fa 35 52 ab 6d 3d e3 06 ba 06 38 d5 a0 7c
00:35:36.607: amai: : 80 18 d7 d6 ab 47 80 77 16 97 7d 50 3e 68 48 26
00:35:36.657: amai: : 2e 14 9c 16 43 ed fc 85 6f a3 11 78 29 b5 59 d8
00:35:36.709: amai: : bb e9 80 9d 26 5c 17 34 47 d0 c6 e7 d5 33 f2 5c
00:35:36.759: amai: : 15 4d 53 c7 91 39 c4 46 a7 26 b1 d5 7d 64 86 ee
00:35:36.811: amai: : 97 06 79 f4 03 f7 a6 66 26 b7 7a 34 ba 6d b0 54
00:35:36.861: amai: : da be b2 57 2c d2 96 fa 5a 22 1c 87 36 eb 29 4f
00:35:36.912: amai: : 1e 6e 87 27 b8 39 1a d3 e0 1f 20 f3 3e 41 13 21
00:35:36.963: amai: : 66 9c b3 ea 79 dd 36 e5 9e 15 aa 41 a7 c5 7d cb
00:35:37.014: amai: : 19 7e b6 57 0e 2a d7 e6 52 76 bd e9 1f 19 a5 f9
00:35:37.065: amai: : 27 90 76 45 7c 9a 96 0c d3 02 cc e2 de 6e 62 ff
00:35:37.116: amai: : 49 99 b6 1a a1 be 71 6c 3b 10 c4 12 dd 30 8a ab
00:35:37.167: amai: : 55 57 79 21 e7 c0 e3 80 75 47 0a eb 8e 14 b6 d4
00:35:37.221: amai: : 6f e1 7a 7e 5e 3e 8e 70 e8 8d fc 98 89 15 d9 0b
00:35:37.273: amai: : 79 7c 6f 49 99 df 72 d8 72 fc 5f 11 2c b7 f1 e7
00:35:37.324: amai: : b5 d7 d3 3b 3c 98 c2 28
00:35:37.375: amai: : -----------------------------------------------
00:35:37.426: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 104 bytes]
00:35:37.478: amai: : 30 00 00 00 02 00 00 00 79 fd 9f bc b9 03 2a b6
00:35:37.529: amai: : 83 f5 8f 50 37 10 33 6f 71 12 ae 84 98 16 36 8a
00:35:37.616: amai: : b0 8a 55 1f 9b a9 4f c0 d4 b2 30 e2 cf 71 8d e2
00:35:37.672: amai: : af 1d f3 ea d5 f0 78 84 cc fe 3d e5 78 a1 a3 ef
00:35:37.724: amai: : 2d f2 6e 55 1b fb 44 42 d9 aa 61 95 71 86 a9 9a
00:35:37.775: amai: : f7 ea 15 d9 ef d7 72 1f 9e 11 02 98 46 3f dd c6
00:35:37.825: amai: : 8d ec 29 fd 15 a4 5a d5
00:35:37.876: amai: : -----------------------------------------------
00:35:37.928: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 536 bytes]
00:35:37.978: amai: : 30 00 00 00 0b 00 00 00 c8 02 f2 25 ea 27 bd af
00:35:38.030: amai: : db 2d d5 07 60 b2 2b 9d 5f df b7 26 26 30 7c 59
00:35:38.080: amai: : 80 bc b1 40 42 61 93 f5 aa a1 02 19 97 5a 35 af
00:35:38.131: amai: : ba 56 af c0 d5 79 1b 42 1a c9 34 16 75 5f 91 c4
00:35:38.183: amai: : 72 09 ae 34 f8 84 2c c3 5c 2f 55 cf 2d 9e 66 cd
00:35:38.233: amai: : 7c 48 10 71 4b b5 c1 c9 de a1 24 cb 11 0d 85 c2
00:35:38.283: amai: : ff 8f 01 ab 1d d6 a2 97 1b d4 69 a9 54 fe de 3a
00:35:38.335: amai: : 83 7f 8c 64 a7 8e a5 0b 8f 93 88 3a 41 ae 2b 28
00:35:38.385: amai: : 15 49 40 d6 19 38 c3 f0 e2 1b 1e 6e 81 d0 07 73
00:35:38.436: amai: : 10 da 1b c3 65 d9 a2 db 8b a0 37 db 69 91 78 77
00:35:38.489: amai: : 5e fd 83 da 84 b1 2d bd f6 68 d5 db f4 c0 17 48
00:35:38.539: amai: : 52 cb 07 09 53 7e 68 06 b7 ee 91 18 c7 5a f1 a0
00:35:38.591: amai: : cb e5 10 55 ef 4c 04 dd 99 6a 0d 9c 37 62 04 73
00:35:38.642: amai: : 4f 37 00 df fe f8 27 20 40 e8 77 55 d3 71 ae a9
00:35:38.693: amai: : a9 8c c0 61 5b e0 06 d1 02 df bb d7 54 63 85 0e
00:35:38.768: amai: : 25 c5 50 79 60 c1 95 fe d6 98 58 88 d8 89 ff 3e
00:35:38.819: amai: : 5b 92 81 a6 82 7e fb 0c a0 d0 97 f4 32 0b 3a 7a
00:35:38.872: amai: : 4a ac d0 ee ff 81 cf 4d cc 34 30 07 d0 09 22 11
00:35:38.924: amai: : 1b 00 6b ae c9 b4 e7 96 a5 5e ff 0e 08 d0 c4 65
00:35:38.974: amai: : 93 e6 4e 4f f7 09 a0 e9 0e a7 b5 53 76 ef 5f f4
00:35:39.026: amai: : b6 86 e8 5b fd e7 04 81 58 a6 5c ff c0 6c 73 6a
00:35:39.077: amai: : da 00 d1 4f fe 15 5d 8b 9a 69 3c a6 71 6a cc 6b
00:35:39.128: amai: : 7c 75 63 d9 85 e7 71 5a ff ea 56 8a 61 56 52 5f
00:35:39.179: amai: : 6d ba ac b4 9e a0 a5 65 f2 2c ab 6e 9b 8e 79 9e
00:35:39.230: amai: : 6b f4 77 3b 46 54 84 1a e8 50 fa b6 93 5d 4b b9
00:35:39.281: amai: : 36 1d 19 46 fd 4b 56 ca 3d 86 ee 48 d8 6e 38 4c
00:35:39.333: amai: : 7e 90 0f 96 f3 6b de 22 c8 a2 d9 69 76 6a b6 a2
00:35:39.384: amai: : b9 a2 c1 9c f8 76 8d f9 00 d2 88 b7 ca 44 ae 1c
00:35:39.435: amai: : a9 6a 3d b5 d5 c5 75 63 9b 86 de 5e 29 cd 26 45
00:35:39.485: amai: : 3d af 7c 1a 54 a5 b0 f3 14 46 1d a8 1c ae ee de
00:35:39.536: amai: : ea 44 4f 21 0f 0a db fb d0 5e 60 5d f0 6f aa 90
00:35:39.592: amai: : ac 20 dd 3a fa bf 33 b0 21 86 42 06 4b fa 8f 00
00:35:39.644: amai: : 41 c7 8a e1 c1 51 92 9d 22 a6 4e c3 b1 f9 c4 d4
00:35:39.695: amai: : 04 ea ec e5 ac 35 8d 00
00:35:39.746: amai: : -----------------------------------------------
00:35:39.797: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 344 bytes]
00:35:39.849: amai: : 30 00 00 00 07 00 00 00 30 d7 6f 8c 4e bf ed ed
00:35:39.900: amai: : d7 4c a0 cb c0 57 14 ba 2a c6 b9 00 06 45 df 39
00:35:39.951: amai: : a7 4f 6a 6f f0 9f 7b d6 2e 83 90 7a 73 83 4e 2e
00:35:40.002: amai: : ec ec cf 7f 92 bf 99 73 c5 16 aa 8d 3b 45 7c 63
00:35:40.054: amai: : 6c 68 26 93 70 99 c0 d2 3a 13 f2 c3 70 1a 38 8b
00:35:40.108: amai: : 3c 8f e4 bc 20 73 28 1b 0c 44 62 61 03 69 88 4c
00:35:40.160: amai: : 4a ba ba 8e 97 b6 de be 9e 3e 94 54 7b 6b 5a a1
00:35:40.211: amai: : 19 38 30 a5 f3 00 2c cd b6 cf d9 54 77 29 f3 a7
00:35:40.262: amai: : 13 3c 74 94 3d 0b b0 59 6c 05 87 f1 97 37 8a d9
00:35:40.314: amai: : df 6c 74 e0 7c 23 d1 a2 c5 16 aa 8d 3b 45 7c 63
00:35:40.449: amai: : 6c 68 26 93 70 99 c0 d2 3a 13 f2 c3 70 1a 38 8b
00:35:40.500: amai: : 3c 8f e4 bc 20 73 28 1b 0c 44 62 61 03 69 88 4c
00:35:40.552: amai: : 4a ba ba 8e 97 b6 de be f7 f1 e2 e2 9b 40 85 92
00:35:40.604: amai: : e9 a4 f8 85 44 de 3c 3c d6 4a 69 14 88 e4 56 30
00:35:40.658: amai: : 16 d8 5a fc bc 5b fe 8e 23 bd e5 6a 05 fd 11 9c
00:35:40.709: amai: : 57 89 16 67 0c a1 bf 7b fc 11 28 49 0c 92 f9 7c
00:35:40.761: amai: : 76 8f 31 74 24 c5 c5 34 e7 25 f7 76 42 84 d1 cf
00:35:40.845: amai: : 1c 7b fe f6 9b a1 ee 9e 5d 5f e7 34 ed 6a af d5
00:35:40.931: amai: : 22 a9 13 7c df 74 88 f2 d1 3e 6a d9 0e ae 0a 61
00:35:41.014: amai: : 1f 8a 55 28 4b e5 11 3b c9 1c 3b 94 a2 c8 d7 21
00:35:41.099: amai: : 19 7d 98 c9 17 1d 63 76 67 ae 91 95 f2 14 69 24
00:35:41.157: amai: : 78 11 dc 12 73 ea 5d ac
00:35:41.208: amai: : -----------------------------------------------
00:35:41.260: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 680 bytes]
00:35:41.311: amai: : 30 00 00 00 0e 00 00 00 4f 01 10 c8 21 80 97 1f
00:35:41.362: amai: : b4 50 59 c9 b0 9b 6b ff 9a 72 a3 d3 3d 81 07 46
00:35:41.412: amai: : 9a 3d 2f 75 09 a8 6e ad 45 aa 81 a8 9d 9a 5e ef
00:35:41.463: amai: : 1f 0c 9e d4 97 8a d9 3a eb 9f f0 b1 47 aa b3 5d
00:35:41.514: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:35:41.565: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:35:41.616: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:35:41.667: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:35:41.719: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:35:41.770: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:35:41.821: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:35:41.875: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:35:41.926: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:35:41.977: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:35:42.028: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:35:42.079: amai: : 83 c8 b9 42 91 dd 6f aa f7 f0 da 04 88 29 b8 43
00:35:42.130: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:35:42.182: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:35:42.289: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:35:42.342: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:35:42.393: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:35:42.444: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:35:42.495: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:35:42.546: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:35:42.597: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:35:42.648: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:35:42.700: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:35:42.751: amai: : fc 40 88 5f 79 a0 20 89 14 a4 e9 8d e5 90 b2 b8
00:35:42.802: amai: : f9 12 c9 5a ef 91 70 49 52 2f 91 86 4b e3 fb 9d
00:35:42.853: amai: : c3 34 4a b1 31 53 fb 0e 00 04 4f 08 2b af f1 13
00:35:42.904: amai: : ff f7 37 ae e8 31 a6 b1 40 7e a2 ec 68 0c 19 11
00:35:42.955: amai: : 85 5a 2c 49 a9 16 33 e3 b9 4f 5c 0d cf bc 46 ae
00:35:43.113: amai: : 5f bc 42 3d b6 c1 08 bb eb 57 6b c6 33 da 5b a4
00:35:43.220: amai: : 2f e0 e8 cb 73 91 ca 28 49 a1 4b d4 f5 b4 a1 f4
00:35:43.277: amai: : 97 8a 93 9c 75 37 27 33 65 07 ab 50 37 66 30 a8
00:35:43.336: amai: : e5 01 e9 94 ff e0 7a eb 0d 2c 4d 58 22 5b e7 0a
00:35:43.387: amai: : 71 ec 46 a2 aa 04 8d 26 ef dc 34 80 82 fe 22 e8
00:35:43.437: amai: : 35 dd 1a 45 53 9a 56 c1 53 1b df c3 77 f5 9c 9e
00:35:43.488: amai: : c0 00 90 d7 34 a6 bc 17 b9 cd 73 70 e7 2a ae 31
00:35:43.539: amai: : 80 b7 c8 1e 50 b1 ce 72 9d e7 f6 bd cb 55 bd a8
00:35:43.592: amai: : 2f 7f 62 d4 7a 01 da 6a db f7 db ee 86 77 2b 6d
00:35:43.643: amai: : 1e 1e 67 ef 2c ac d7 63 56 f3 90 7d 96 86 2c 82
00:35:43.695: amai: : 2a 90 e0 ec 1f da 40 c3
00:35:43.745: amai: : -----------------------------------------------
00:35:43.804: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 248 bytes]
00:35:43.855: amai: : 30 00 00 00 05 00 00 00 57 ad 80 ac 99 4f 9c 5a
00:35:43.906: amai: : 2b 62 11 14 f4 fe 61 a3 6f 52 0a 61 bf 48 75 ff
00:35:43.962: amai: : ea de 86 71 17 88 8e d1 31 8e 9f 8b 66 e7 37 be
00:35:44.012: amai: : 5f fa 44 46 b8 5f 1a 2a 44 88 de db cd 51 3b bd
00:35:44.063: amai: : 23 6c 05 01 48 42 34 74 2c a3 14 c5 c7 d4 1f d6
00:35:44.114: amai: : 06 c7 e2 a9 a1 96 e2 76 0f 9f d7 83 2b ed 88 b3
00:35:44.165: amai: : 65 6f b6 0f ad 8d b4 f3 9f 85 a8 c7 d4 ad 4c 6c
00:35:44.216: amai: : b7 95 f1 2b 25 df 6e 70 d0 b6 02 59 54 9a a7 27
00:35:44.267: amai: : 79 fd e2 6f 13 83 f4 f7 42 ba 57 47 6e ba a7 0f
00:35:44.318: amai: : f3 9c b9 2f 23 eb 17 6e 0c fe 11 2c 08 c9 bc e3
00:35:44.371: amai: : 48 32 0a 23 4e b8 77 51 04 3f 4e ab 8e 7d 39 cf
00:35:44.448: amai: : ae 7b 5c 2f 1e 08 f2 e4 49 b5 90 c4 78 43 01 1c
00:35:44.523: amai: : b5 e8 73 c0 78 59 ed 49 d3 41 e0 3e 26 0e 5a 36
00:35:44.602: amai: : 76 29 21 ab 35 9e 00 6b 8d 92 9b fc 55 85 31 96
00:35:44.653: amai: : 61 c5 7b 3d 31 a5 c8 2b c4 fb 9c 9c fd b1 8e 89
00:35:44.704: amai: : 1b 2b e5 35 b7 2e fd 47
00:35:44.755: amai: : -----------------------------------------------
00:35:44.807: amai: BbfwReaderFindAndCopyFileData: failed to find bbfw item "vinyl/update/main/signedprofile.der": File error
00:35:44.861: amai: BbfwReaderFindAndCopyFileData: failed to find bbfw item "vinyl/update/gold/signedprofile.der": File error
00:35:44.912: amai: AMAuthInstallIsICE19BBGoldCertIDECDSA: GoldCertId: 1F3F5BDF
00:35:44.963: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BasebandFirmware to Manifest to personalize later
00:35:45.013: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting OS to Manifest to personalize later
00:35:45.064: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RecoveryMode to Manifest to personalize later
00:35:45.115: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Liquid to Manifest to personalize later
00:35:45.167: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow0 to Manifest to personalize later
00:35:45.218: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AVE to Manifest to personalize later
00:35:45.268: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ANE to Manifest to personalize later
00:35:45.319: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,HapticAssets to Manifest to personalize later
00:35:45.370: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryPlugin to Manifest to personalize later
00:35:45.421: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreSEP to Manifest to personalize later
00:35:45.472: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ISP to Manifest to personalize later
00:35:45.524: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SEP to Manifest to personalize later
00:35:45.574: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBoot to Manifest to personalize later
00:35:45.625: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreTrustCache to Manifest to personalize later
00:35:45.678: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet1 to Manifest to personalize later
00:35:45.729: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting DeviceTree to Manifest to personalize later
00:35:45.781: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AudioCodecFirmware to Manifest to personalize later
00:35:45.833: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting PMP to Manifest to personalize later
00:35:45.922: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LeapHaptics to Manifest to personalize later
00:35:45.974: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting StaticTrustCache to Manifest to personalize later
00:35:46.025: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging0 to Manifest to personalize later
00:35:46.079: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LLB to Manifest to personalize later
00:35:46.131: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow1 to Manifest to personalize later
00:35:46.181: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryFull to Manifest to personalize later
00:35:46.232: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AppleLogo to Manifest to personalize later
00:35:46.283: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SIO to Manifest to personalize later
00:35:46.334: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging1 to Manifest to personalize later
00:35:46.385: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting GFX to Manifest to personalize later
00:35:46.436: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AOP to Manifest to personalize later
00:35:46.487: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet0 to Manifest to personalize later
00:35:46.538: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting WCHFirmwareUpdater to Manifest to personalize later
00:35:46.588: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Multitouch to Manifest to personalize later
00:35:46.639: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbProvisioningManifestKeyHash = <CFDa
                     ta 0x7f9603c229d0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x238c5118db979840969fb4dba3ab2db3 ... 162
                     9e2a30e1df392}
00:35:46.690: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbActivationManifestKeyHash = <CFData
                     0x7f9603c6dda0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x1b41607650ebf11c6b39f41cb267dc64 ... 055803
                     e1ef81c870}
00:35:46.742: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbFDRSecurityKeyHash = <CFData 0x7f9
                     603c0e7c0 [0x7fff88086cc0]>{length = 0, capacity = 0, bytes = 0x}
00:35:46.794: amai: _AMAuthInstallBundleCreateServerRequestDictionary: ticketPath amai/apimg4ticket.der , withApTicket is False,  (!True
                     && ( False || False))
00:35:46.845: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreLogo"
00:35:46.897: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreDeviceTree"
00:35:46.948: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreKernelCache"
00:35:46.999: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreRamDisk"
00:35:47.050: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "OSRamdisk" not part of manifest, skipping
00:35:47.101: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBEC"
00:35:47.152: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBSS"
00:35:47.204: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "KernelCache"
00:35:47.255: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftap" entry
00:35:47.306: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfta" entry
00:35:47.409: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftsp" entry
00:35:47.532: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfts" entry
00:35:47.594: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,SystemVolumeCanonicalMetadata"
00:35:47.646: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolumeCanonicalMetadata" not part of manif
                     est, skipping
00:35:47.698: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "BaseSystemVolume" not part of manifest, skipping
00:35:47.749: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,BaseSystemVolume" not part of manifest, skipping
00:35:47.800: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SystemVolume"
00:35:47.850: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolume" not part of manifest, skipping
00:35:47.901: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Ap,BaseSystemTrustCache" not part of manifest, skipping
00:35:47.952: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Diags" not part of manifest, skipping
00:35:48.004: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "CFELoader" not part of manifest, skipping
00:35:48.055: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "RBM" not part of manifest, skipping
00:35:48.105: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PHLEET" not part of manifest, skipping
00:35:48.156: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PERTOS" not part of manifest, skipping
00:35:48.207: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PEHammer" not part of manifest, skipping
00:35:48.257: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Alamo" not part of manifest, skipping
00:35:48.308: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "BasebandFirmware" has been previously personalized; sk
                     ipping it
00:35:48.366: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "OS" entry
00:35:48.417: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RecoveryMode"
00:35:48.467: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Liquid"
00:35:48.544: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow0"
00:35:48.595: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AVE"
00:35:48.648: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ANE"
00:35:48.733: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,HapticAssets"
00:35:48.784: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryPlugin"
00:35:48.834: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreSEP"
00:35:48.885: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ISP"
00:35:48.936: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SEP"
00:35:48.987: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBoot"
00:35:49.038: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreTrustCache"
00:35:49.091: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet1"
00:35:49.143: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "DeviceTree"
00:35:49.194: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AudioCodecFirmware"
00:35:49.248: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "PMP"
00:35:49.300: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LeapHaptics"
00:35:49.361: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "StaticTrustCache"
00:35:49.416: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging0"
00:35:49.466: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LLB"
00:35:49.517: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow1"
00:35:49.569: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryFull"
00:35:49.621: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AppleLogo"
00:35:49.703: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SIO"
00:35:49.755: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging1"
00:35:49.807: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "GFX"
00:35:49.878: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AOP"
00:35:49.943: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet0"
00:35:49.994: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "WCHFirmwareUpdater"
00:35:50.045: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Multitouch"
00:35:50.096: amai: AMSupportPlatformCreateBufferFromNativeFilePath: open failed: No such file or directory
00:35:50.147: amai: AMSupportPlatformCreateBufferFromNativeFilePath: /usr/local/standalone/firmware/device_map.plist
00:35:50.199: amai: AMAuthInstallApCopyDeviceEntryFromDeviceMap: Failed to read devicemap from file:///usr/local/standalone/firmwar
                     e/device_map.plist
00:35:50.258: amai: AMAuthInstallApImg4ServerRequestAddUIDMode: Could not check if UID mode is required.
00:35:50.309: amai: _AMAuthInstallBundleCreateServerRequestDictionary: nothing to be done
00:35:50.359: Setting kAMRestoreOptionsiBootEANNuke.
00:35:50.410: requested restore behavior: Erase
00:35:50.410:  Flash mode: Don't Retain User's Data While Flashing
00:35:50.460: overwrite InstallDiags to false
00:35:50.510: IPv6 @ locationID=0x26400000, NCM 0x100000b11: found remote address [fe80::98f5:bfff:feff:2a0%en3]
00:35:50.561: <Restore Device 0x7f9603d65960>: operation 3 progress -1
00:35:50.611: sock   8: connected to  [fe80::98f5:bfff:feff:2a0%en3]:62078 as [fe80::14aa:5f22:bd0d:28ad%en3]:51518
00:35:50.695: sock   8: set SO_KEEPALIVE=1
00:35:50.748: <Restore Device 0x7f9603d65960>: operation 4 progress -1
00:35:50.800: device did not return saved USB log
00:35:50.852: device did not return saved panic log
00:35:50.902: connected to service com.apple.mobile.restored
00:35:50.954: using protocol version 15
00:35:51.004: supports value queries: 1
00:35:51.056: unable to open device_map.txt: No such file or directory
00:35:51.107: board config = d421ap
00:35:51.158: no value returned for BootArgs
00:35:51.209: _copyDeviceProperty() failed for restore bootargs
00:35:51.293: no value returned for MarketingPartNumber
00:35:51.373: _copyDeviceProperty() failed for mpn
00:35:51.424: requested restore behavior: Erase
00:35:51.425:  Flash mode: Don't Retain User's Data While Flashing
00:35:51.475: Can't return padding information since it's not in the Restore.plist, looking in BuildManifest.plist
00:35:51.525: requested restore behavior: Erase
00:35:51.525:  Flash mode: Don't Retain User's Data While Flashing
00:35:51.576: Established SOCKS proxy for device
00:35:51.626: sock  11: connected to  [fe80::98f5:bfff:feff:2a0%en3]:1082 as [fe80::14aa:5f22:bd0d:28ad%en3]:51519
00:35:51.676: Restore attestation requires Apple Silicon host
00:35:51.727: Restore security attestation: UNAVAILABLE
00:35:51.778: Completed checkpoint id: 0x655 (is_host_compatible)
00:35:51.828: Started checkpoint id: 0x604 (set_weight_from_options)
00:35:51.878: Completed checkpoint id: 0x604 (set_weight_from_options)
00:35:51.929: Started checkpoint id: 0x68F (libauthinstall_callback)
00:35:51.980: Completed checkpoint id: 0x68F (libauthinstall_callback)
00:35:52.034: Started checkpoint id: 0x608 (device_has_hoover)
00:35:52.085: Completed checkpoint id: 0x608 (device_has_hoover)
00:35:52.135: Started checkpoint id: 0x60B (update_ticket)
00:35:52.186: Completed checkpoint id: 0x60B (update_ticket)
00:35:52.236: Started checkpoint id: 0x60D (wait_for_storage)
00:35:52.287: <Restore Device 0x7f9603d65960>: operation 28 progress -1
00:35:52.287:  Waiting for the preparation of drive boot sector
00:35:52.355: Completed checkpoint id: 0x60D (wait_for_storage)
00:35:52.461: Started checkpoint id: 0x60E (update_NAND_firmware)
00:35:52.512: <Restore Device 0x7f9603d65960>: operation 58 progress -1
00:35:52.512:  Updating S3E firmware
00:35:52.563: Completed checkpoint id: 0x60E (update_NAND_firmware)
00:35:52.613: Started checkpoint id: 0x60F (clear_remap_variable)
00:35:52.666: Completed checkpoint id: 0x60F (clear_remap_variable)
00:35:52.717: Started checkpoint id: 0x65C (print_nvram_variables)
00:35:52.769: Completed checkpoint id: 0x65C (print_nvram_variables)
00:35:52.823: Started checkpoint id: 0x610 (asp_nand_set_writable)
00:35:52.874: Completed checkpoint id: 0x610 (asp_nand_set_writable)
00:35:52.924: Started checkpoint id: 0x613 (find_filesystem_partitions)
00:35:52.994: Completed checkpoint id: 0x613 (find_filesystem_partitions)
00:35:53.045: Started checkpoint id: 0x67E (verify_storage_for_update)
00:35:53.096: Completed checkpoint id: 0x67E (verify_storage_for_update)
00:35:53.146: Started checkpoint id: 0x609 (load_sep_os)
00:35:53.196: <Restore Device 0x7f9603d65960>: operation 35 progress -1
00:35:53.227:  Sending the sub-firmware of the drive boot sector (NAND)
00:35:53.308: requested restore behavior: Erase
00:35:53.309:  Flash mode: Don't Retain User's Data While Flashing
00:35:53.359: Completed checkpoint id: 0x609 (load_sep_os)
00:35:53.410: Started checkpoint id: 0x693 (preload_keys_for_fsck)
00:35:53.460: Completed checkpoint id: 0x693 (preload_keys_for_fsck)
00:35:53.510: Started checkpoint id: 0x665 (fsck_filesystems)
00:35:53.584: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:35:53.585:  Closing the mounting of the drive
00:35:53.637: Completed checkpoint id: 0x665 (fsck_filesystems)
00:35:53.719: Started checkpoint id: 0x614 (mount_system_partition)
00:35:53.770: Completed checkpoint id: 0x614 (mount_system_partition)
00:35:53.821: Started checkpoint id: 0x696 (fix_cache_delete)
00:35:53.871: Completed checkpoint id: 0x696 (fix_cache_delete)
00:35:53.922: Started checkpoint id: 0x65D (delete_mobilebackups)
00:35:53.972: Completed checkpoint id: 0x65D (delete_mobilebackups)
00:35:54.023: Started checkpoint id: 0x6C1 (clean_update_volume)
00:35:54.073: Completed checkpoint id: 0x6C1 (clean_update_volume)
00:35:54.124: Started checkpoint id: 0x6A3 (space_checks)
00:35:54.174: Completed checkpoint id: 0x6A3 (space_checks)
00:35:54.229: Started checkpoint id: 0x69F (clear_mobile_gestalt_cache)
00:35:54.279: Completed checkpoint id: 0x69F (clear_mobile_gestalt_cache)
00:35:54.330: Started checkpoint id: 0x654 (read_previous_os_build_version)
00:35:54.380: Completed checkpoint id: 0x654 (read_previous_os_build_version)
00:35:54.430: Started checkpoint id: 0x697 (downgrade_check)
00:35:54.481: Completed checkpoint id: 0x697 (downgrade_check)
00:35:54.537: Started checkpoint id: 0x615 (copy_hardware_info)
00:35:54.588: Completed checkpoint id: 0x615 (copy_hardware_info)
00:35:54.639: Started checkpoint id: 0x616 (fdr_create)
00:35:54.689: no override trust object found
00:35:54.740: no override trust object found
00:35:54.794: Completed checkpoint id: 0x616 (fdr_create)
00:35:54.848: Started checkpoint id: 0x617 (fdr_save_data)
00:35:54.899: Completed checkpoint id: 0x617 (fdr_save_data)
00:35:54.949: Started checkpoint id: 0x618 (store_baseband_migration)
00:35:55.006: Completed checkpoint id: 0x618 (store_baseband_migration)
00:35:55.093: Started checkpoint id: 0x619 (check_for_restore_log)
00:35:55.143: <Restore Device 0x7f9603d65960>: operation 44 progress -1
00:35:55.193: Completed checkpoint id: 0x619 (check_for_restore_log)
00:35:55.243: Started checkpoint id: 0x61A (check_for_ota_logs)
00:35:55.294: <Restore Device 0x7f9603d65960>: operation 44 progress -1
00:35:55.344: Completed checkpoint id: 0x61A (check_for_ota_logs)
00:35:55.395: Started checkpoint id: 0x61B (submit_update_stats)
00:35:55.446: sock  12: connected to  [fe80::98f5:bfff:feff:2a0%en3]:49161 as [fe80::14aa:5f22:bd0d:28ad%en3]:51521
00:35:55.498: [PurpleReverseProxy]: Feb 05 00:35:41 iTunesFlash[4281] <Error>: RPSocket.cpp:228(signal): No client callback, missing eve
                     nt 8 for socket 0x7f9603c690e0
00:35:55.549: Completed checkpoint id: 0x61B (submit_update_stats)
00:35:55.599: Started checkpoint id: 0x661 (read_persistent_files)
00:35:55.650: Completed checkpoint id: 0x661 (read_persistent_files)
00:35:55.704: Started checkpoint id: 0x61D (unmount_unconditionally)
00:35:55.754: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:35:55.754:  Closing the mounting of the drive
00:35:55.805: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:35:55.805:  Closing the mounting of the drive
00:35:55.855: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:35:55.857:  Closing the mounting of the drive
00:35:55.907: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:35:55.907:  Closing the mounting of the drive
00:35:55.957: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:35:55.958:  Closing the mounting of the drive
00:35:56.008: Completed checkpoint id: 0x61D (unmount_unconditionally)
00:35:56.058: Started checkpoint id: 0x64E (clean_nand)
00:35:56.109: Completed checkpoint id: 0x64E (clean_nand)
00:35:56.160: Started checkpoint id: 0x61F (format_effaceable_storage)
00:35:56.212: Completed checkpoint id: 0x61F (format_effaceable_storage)
00:35:56.262: Started checkpoint id: 0x68A (format_ean_storage)
00:35:56.313: Completed checkpoint id: 0x68A (format_ean_storage)
00:35:56.364: Started checkpoint id: 0x621 (create_filesystem_partitions)
00:35:56.414: <Restore Device 0x7f9603d65960>: operation 11 progress -1
00:35:56.414:  Dividing the drive
00:35:56.465: Completed checkpoint id: 0x621 (create_filesystem_partitions)
00:35:56.516: Started checkpoint id: 0x677 (perform_main_os_prepare)
00:35:56.567: Started checkpoint id: 0x660 (update_partitions_for_apfs)
00:35:56.622: Completed checkpoint id: 0x660 (update_partitions_for_apfs)
00:35:56.672: Started checkpoint id: 0x622 (reload_filesystem_partitions)
00:35:56.723: Completed checkpoint id: 0x622 (reload_filesystem_partitions)
00:35:56.774: Started checkpoint id: 0x160D (delete_recovery_partition)
00:35:56.825: Completed checkpoint id: 0x160D (delete_recovery_partition)
00:35:56.875: Started checkpoint id: 0x658 (format_media)
00:35:56.927: <Restore Device 0x7f9603d65960>: operation 12 progress -1
00:35:56.927:  Establishing file system
00:35:56.977: Completed checkpoint id: 0x658 (format_media)
00:35:57.028: Started checkpoint id: 0x659 (find_volumes_after_format)
00:35:57.078: Completed checkpoint id: 0x659 (find_volumes_after_format)
00:35:57.128: Started checkpoint id: 0x6B3 (prepare_for_system_image)
00:35:57.179: Completed checkpoint id: 0x6B3 (prepare_for_system_image)
00:35:57.230: Started checkpoint id: 0x65A (baseband_migration_data)
00:35:57.281: Completed checkpoint id: 0x65A (baseband_migration_data)
00:35:57.331: Started checkpoint id: 0x675 (init_gigalocker)
00:35:57.383: Completed checkpoint id: 0x675 (init_gigalocker)
00:35:57.438: Started checkpoint id: 0x68C (init_permanent_update_volume)
00:35:57.491: Completed checkpoint id: 0x68C (init_permanent_update_volume)
00:35:57.541: Started checkpoint id: 0x626 (mount_filesystem)
00:35:57.592: <Restore Device 0x7f9603d65960>: operation 16 progress -1
00:35:57.593:  Mounting file system
00:35:57.643: <Restore Device 0x7f9603d65960>: operation 16 progress -1
00:35:57.644:  Mounting file system
00:35:57.694: <Restore Device 0x7f9603d65960>: operation 16 progress -1
00:35:57.695:  Mounting file system
00:35:57.745: <Restore Device 0x7f9603d65960>: operation 16 progress -1
00:35:57.745:  Mounting file system
00:35:57.796: Completed checkpoint id: 0x626 (mount_filesystem)
00:35:57.847: Started checkpoint id: 0x65B (restore_system_image)
00:35:57.897: Completed checkpoint id: 0x65B (restore_system_image)
00:35:57.948: Started checkpoint id: 0x662 (write_persistent_files)
00:35:58.001: <Restore Device 0x7f9603d65960>: operation 13 progress 0
00:35:58.006:  Sending file system via ASR 0%
00:35:58.056: sock  12: connected to  [usbmux_3]:12346
00:35:58.107: ASR progress: Initialized communication with client
00:35:58.158: Completed checkpoint id: 0x662 (write_persistent_files)
00:35:58.208: Completed checkpoint id: 0x677 (perform_main_os_prepare)
00:35:58.259: Started checkpoint id: 0x67A (perform_short_prepare)
00:35:58.309: Completed checkpoint id: 0x67A (perform_short_prepare)
00:35:58.361: Started checkpoint id: 0x67B (perform_restore_installing)
00:35:58.413: Started checkpoint id: 0x627 (fdr_restore_saved_data)
00:35:58.464: Completed checkpoint id: 0x627 (fdr_restore_saved_data)
00:35:58.514: Started checkpoint id: 0x69A (update_device_firmware_pre_fdr)
00:35:58.565: ASR progress: Starting to send payload
00:35:58.671: Started checkpoint id: 0x130C (update_aht)
00:35:58.723: Completed checkpoint id: 0x130C (update_aht)
00:35:58.774: Completed checkpoint id: 0x69A (update_device_firmware_pre_fdr)
00:35:58.825: Started checkpoint id: 0x69B (fdr_prepare)
00:35:58.875: <Restore Device 0x7f9603d65960>: operation 13 progress 0
00:35:58.876:  Sending file system via ASR 0%
00:35:58.926: AsyncDataRequestMsg: URLAsset: Switching to background queue to prevent restore queue deadlock
00:35:58.976: sock  14: connected to  [usbmux_3]:49165
00:35:59.027: Completed checkpoint id: 0x69B (fdr_prepare)
00:35:59.078: Started checkpoint id: 0x652 (clear_fips_data_file)
00:35:59.130: Completed checkpoint id: 0x652 (clear_fips_data_file)
00:35:59.180: Started checkpoint id: 0x634 (fdr_recover)
00:35:59.231: Completed checkpoint id: 0x634 (fdr_recover)
00:35:59.281: Started checkpoint id: 0x67D (fdr_auto_challenge_claim)
00:35:59.332: Completed checkpoint id: 0x67D (fdr_auto_challenge_claim)
00:35:59.383: Started checkpoint id: 0x635 (update_device_firmware)
00:35:59.435: Started checkpoint id: 0x1311 (update_veridian)
00:35:59.485: <Restore Device 0x7f9603d65960>: operation 66 progress 0
00:35:59.539: Completed checkpoint id: 0x1311 (update_veridian)
00:35:59.590: Started checkpoint id: 0x1320 (update_manta_mcu)
00:35:59.669: Completed checkpoint id: 0x1320 (update_manta_mcu)
00:35:59.747: <Restore Device 0x7f9603d65960>: operation 88 progress 0
00:35:59.824: Started checkpoint id: 0x1300 (update_iBoot)
00:35:59.875: <Restore Device 0x7f9603d65960>: operation 88 progress 100
00:35:59.927: <Restore Device 0x7f9603d65960>: operation 80 progress 1
00:36:00.015: requested restore behavior: Erase
00:36:00.043:  Flash mode: Don't Retain User's Data While Flashing
00:36:00.124: <Restore Device 0x7f9603d65960>: operation 80 progress 1
00:36:00.203: requested restore behavior: Erase
00:36:00.203:  Flash mode: Don't Retain User's Data While Flashing
00:36:00.253: <Restore Device 0x7f9603d65960>: operation 18 progress 0
00:36:00.307: requested restore behavior: Erase
00:36:00.307:  Flash mode: Don't Retain User's Data While Flashing
00:36:00.358: requested restore behavior: Erase
00:36:00.358:  Flash mode: Don't Retain User's Data While Flashing
00:36:00.408: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: 
                     isRecovery = 0, entry = BMU,FirmwareMap
00:36:00.459: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.
                     3_22D64_Restore/Firmware/Veridian/X1442/FirmwareMap.plist
00:36:00.509: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/Veridian/X1442/FirmwareMap.plist
00:36:00.560: amai: _handleFirmwareUpdaterRequest: T200 updater has device-generated RestoreInfo
00:36:00.611: requested restore behavior: Erase
00:36:00.617:  Flash mode: Don't Retain User's Data While Flashing
00:36:00.667: repersonalization is ON for T200 updater
00:36:00.718: amai: AMAuthInstallUpdaterPersonalize: Adding AP fusing information to coprocessor TSS request.
00:36:00.768: amai: AMAuthInstallUpdaterCreateResponse: Updater local signing support: false
00:36:00.819: amai: AMAuthInstallRequestSendSyncWithHeader: SSO function returned NULL and no SSO token was provided, SSO disabl
                     ed.
00:36:00.869: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-request.plist
00:36:00.919: amai: tss_submit_job_with_retry: TSS Connection attempt 1 of 3.  (Will retry if TSS_ERR_SERVER_NOT_REACHABLE.)
00:36:00.979: amai: -[AMSupportStaticURLSession URLSession:didReceiveChallenge:completionHandler:]: Authentication challenge receiv
                     ed.  Method: NSURLAuthenticationMethodServerTrust
00:36:01.030: amai: -[AMSupportStaticURLSession URLSession:didReceiveChallenge:completionHandler:]: Authentication challenge receiv
                     ed.  Method: NSURLAuthenticationMethodServerTrust
00:36:01.081: amai: -[AMSupportStaticURLSession URLSession:didReceiveChallenge:completionHandler:]: Authentication challenge receive
                     d.  Method: NSURLAuthenticationMethodServerTrust
00:36:01.131: amai: AMAuthInstallRequestSendSyncWithHeader: received tss response (server version: 2.1.0)
00:36:01.182: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-response.plist
00:36:01.232: amai: AMAuthInstallUpdaterPersonalize: Stashing T200 ticket(s) in bundle (LoopInstance=(null))
00:36:01.283: 2025-02-05 00:35:48.000 iTunesFlash[4281:6d2b]: URL Request: Server Response 200: (body length 241)
00:36:01.333: sock  14: closed
00:36:01.383: 00:36:01.434: Completed checkpoint id: 0x1300 (update_iBoot)
00:36:01.484: Started checkpoint id: 0x1312 (update_ean)
00:36:01.536: <Restore Device 0x7f9603d65960>: operation 80 progress 1
00:36:01.587: requested restore behavior: Erase
00:36:01.620:  Flash mode: Don't Retain User's Data While Flashing
00:36:01.716: <Restore Device 0x7f9603d65960>: operation 80 progress 1
00:36:01.813: requested restore behavior: Erase
00:36:01.813:  Flash mode: Don't Retain User's Data While Flashing
00:36:01.864: <Restore Device 0x7f9603d65960>: operation 80 progress 1
00:36:01.914: requested restore behavior: Erase
00:36:01.915:  Flash mode: Don't Retain User's Data While Flashing
00:36:01.965: Completed checkpoint id: 0x1312 (update_ean)
00:36:02.016: Started checkpoint id: 0x130A (install_fud)
00:36:02.067: <Restore Device 0x7f9603d65960>: operation 36 progress 1
00:36:02.067:  Sending FUD sub-firmware
00:36:02.118: requested restore behavior: Erase
00:36:02.118:  Flash mode: Don't Retain User's Data While Flashing
00:36:02.168: <Restore Device 0x7f9603d65960>: operation 66 progress 100
00:36:02.219: requested restore behavior: Erase
00:36:02.219:  Flash mode: Don't Retain User's Data While Flashing
00:36:02.269: <Restore Device 0x7f9603d65960>: operation 36 progress 6
00:36:02.269:  Sending FUD sub-firmware
00:36:02.320: requested restore behavior: Erase
00:36:02.320:  Flash mode: Don't Retain User's Data While Flashing
00:36:02.370: <Restore Device 0x7f9603d65960>: operation 36 progress 13
00:36:02.371:  Sending FUD sub-firmware
00:36:02.422: requested restore behavior: Erase
00:36:02.424:  Flash mode: Don't Retain User's Data While Flashing
00:36:02.475: <Restore Device 0x7f9603d65960>: operation 36 progress 20
00:36:02.475:  Sending FUD sub-firmware
00:36:02.526: requested restore behavior: Erase
00:36:02.526:  Flash mode: Don't Retain User's Data While Flashing
00:36:02.576: <Restore Device 0x7f9603d65960>: operation 36 progress 26
00:36:02.577:  Sending FUD sub-firmware
00:36:02.627: requested restore behavior: Erase
00:36:02.627:  Flash mode: Don't Retain User's Data While Flashing
00:36:02.677: <Restore Device 0x7f9603d65960>: operation 36 progress 33
00:36:02.678:  Sending FUD sub-firmware
00:36:02.728: requested restore behavior: Erase
00:36:02.728:  Flash mode: Don't Retain User's Data While Flashing
00:36:02.778: <Restore Device 0x7f9603d65960>: operation 36 progress 40
00:36:02.778:  Sending FUD sub-firmware
00:36:02.829: requested restore behavior: Erase
00:36:02.829:  Flash mode: Don't Retain User's Data While Flashing
00:36:02.879: <Restore Device 0x7f9603d65960>: operation 36 progress 46
00:36:02.879:  Sending FUD sub-firmware
00:36:02.930: requested restore behavior: Erase
00:36:02.931:  Flash mode: Don't Retain User's Data While Flashing
00:36:02.981: <Restore Device 0x7f9603d65960>: operation 36 progress 53
00:36:02.981:  Sending FUD sub-firmware
00:36:03.032: requested restore behavior: Erase
00:36:03.032:  Flash mode: Don't Retain User's Data While Flashing
00:36:03.082: <Restore Device 0x7f9603d65960>: operation 13 progress 1
00:36:03.082:  Sending file system via ASR 1%
00:36:03.133: <Restore Device 0x7f9603d65960>: operation 36 progress 60
00:36:03.134:  Sending FUD sub-firmware
00:36:03.185: requested restore behavior: Erase
00:36:03.185:  Flash mode: Don't Retain User's Data While Flashing
00:36:03.235: <Restore Device 0x7f9603d65960>: operation 36 progress 66
00:36:03.236:  Sending FUD sub-firmware
00:36:03.286: requested restore behavior: Erase
00:36:03.286:  Flash mode: Don't Retain User's Data While Flashing
00:36:03.337: <Restore Device 0x7f9603d65960>: operation 36 progress 73
00:36:03.337:  Sending FUD sub-firmware
00:36:03.388: requested restore behavior: Erase
00:36:03.388:  Flash mode: Don't Retain User's Data While Flashing
00:36:03.442: ASR progress: Sending payload
00:36:03.493: <Restore Device 0x7f9603d65960>: operation 36 progress 80
00:36:03.494:  Sending FUD sub-firmware
00:36:03.544: requested restore behavior: Erase
00:36:03.544:  Flash mode: Don't Retain User's Data While Flashing
00:36:03.595: <Restore Device 0x7f9603d65960>: operation 36 progress 86
00:36:03.595:  Sending FUD sub-firmware
00:36:03.645: requested restore behavior: Erase
00:36:03.677:  Flash mode: Don't Retain User's Data While Flashing
00:36:03.762: <Restore Device 0x7f9603d65960>: operation 36 progress 93
00:36:03.797:  Sending FUD sub-firmware
00:36:03.851: requested restore behavior: Erase
00:36:03.863:  Flash mode: Don't Retain User's Data While Flashing
00:36:03.913: <Restore Device 0x7f9603d65960>: operation 36 progress 100
00:36:03.913:  Sending FUD sub-firmware
00:36:03.964: Completed checkpoint id: 0x130A (install_fud)
00:36:04.015: Started checkpoint id: 0x1304 (update_stockholm)
00:36:04.065: <Restore Device 0x7f9603d65960>: operation 55 progress 0
00:36:04.116: Completed checkpoint id: 0x1304 (update_stockholm)
00:36:04.167: Started checkpoint id: 0x1303 (update_baseband_legacy)
00:36:04.218: Completed checkpoint id: 0x1303 (update_baseband_legacy)
00:36:04.269: Started checkpoint id: 0x1310 (update_rose)
00:36:04.320: Completed checkpoint id: 0x1310 (update_rose)
00:36:04.370: Started checkpoint id: 0x1309 (update_se)
00:36:04.421: Completed checkpoint id: 0x1309 (update_se)
00:36:04.479: Started checkpoint id: 0x1322 (update_vinyl)
00:36:04.530: Completed checkpoint id: 0x1322 (update_vinyl)
00:36:04.581: Started checkpoint id: 0x1301 (update_gas_gauge)
00:36:04.631: <Restore Device 0x7f9603d65960>: operation 47 progress -1
00:36:04.683: Completed checkpoint id: 0x1301 (update_gas_gauge)
00:36:04.733: Started checkpoint id: 0x1302 (update_ir_mcu)
00:36:04.785: <Restore Device 0x7f9603d65960>: operation 47 progress -1
00:36:04.864: Completed checkpoint id: 0x1302 (update_ir_mcu)
00:36:04.920: Started checkpoint id: 0x130C (update_aht)
00:36:05.507: <Restore Device 0x7f9603d65960>: operation 36 progress 1
00:36:05.536:  Sending FUD sub-firmware
00:36:05.614: requested restore behavior: Erase
00:36:05.614:  Flash mode: Don't Retain User's Data While Flashing
00:36:05.664: <Restore Device 0x7f9603d65960>: operation 36 progress 6
00:36:05.665:  Sending FUD sub-firmware
00:36:05.715: <Restore Device 0x7f9603d65960>: operation 36 progress 13
00:36:05.715:  Sending FUD sub-firmware
00:36:05.766: <Restore Device 0x7f9603d65960>: operation 36 progress 20
00:36:05.766:  Sending FUD sub-firmware
00:36:05.816: <Restore Device 0x7f9603d65960>: operation 36 progress 26
00:36:05.816:  Sending FUD sub-firmware
00:36:05.867: <Restore Device 0x7f9603d65960>: operation 36 progress 33
00:36:05.867:  Sending FUD sub-firmware
00:36:05.918: <Restore Device 0x7f9603d65960>: operation 36 progress 40
00:36:05.918:  Sending FUD sub-firmware
00:36:05.968: <Restore Device 0x7f9603d65960>: operation 36 progress 46
00:36:05.968:  Sending FUD sub-firmware
00:36:06.018: <Restore Device 0x7f9603d65960>: operation 36 progress 53
00:36:06.019:  Sending FUD sub-firmware
00:36:06.070: requested restore behavior: Erase
00:36:06.070:  Flash mode: Don't Retain User's Data While Flashing
00:36:06.120: <Restore Device 0x7f9603d65960>: operation 36 progress 60
00:36:06.153:  Sending FUD sub-firmware
00:36:06.216: requested restore behavior: Erase
00:36:06.216:  Flash mode: Don't Retain User's Data While Flashing
00:36:06.266: <Restore Device 0x7f9603d65960>: operation 36 progress 66
00:36:06.266:  Sending FUD sub-firmware
00:36:06.316: requested restore behavior: Erase
00:36:06.316:  Flash mode: Don't Retain User's Data While Flashing
00:36:06.367: <Restore Device 0x7f9603d65960>: operation 36 progress 73
00:36:06.367:  Sending FUD sub-firmware
00:36:06.417: <Restore Device 0x7f9603d65960>: operation 36 progress 80
00:36:06.418:  Sending FUD sub-firmware
00:36:06.468: <Restore Device 0x7f9603d65960>: operation 36 progress 86
00:36:06.468:  Sending FUD sub-firmware
00:36:06.519: <Restore Device 0x7f9603d65960>: operation 36 progress 93
00:36:06.519:  Sending FUD sub-firmware
00:36:06.570: <Restore Device 0x7f9603d65960>: operation 36 progress 100
00:36:06.570:  Sending FUD sub-firmware
00:36:06.621: <Restore Device 0x7f9603d65960>: operation 13 progress 2
00:36:06.621:  Sending file system via ASR 2%
00:36:06.672: Completed checkpoint id: 0x130C (update_aht)
00:36:06.722: Started checkpoint id: 0x1306 (update_tcon)
00:36:06.773: Completed checkpoint id: 0x1306 (update_tcon)
00:36:06.825: Started checkpoint id: 0x1307 (update_orion)
00:36:06.888: Completed checkpoint id: 0x1307 (update_orion)
00:36:06.939: Started checkpoint id: 0x1308 (update_madea)
00:36:07.014: Completed checkpoint id: 0x1308 (update_madea)
00:36:07.065: Started checkpoint id: 0x130E (update_peppy)
00:36:07.117: Completed checkpoint id: 0x130E (update_peppy)
00:36:07.168: Started checkpoint id: 0x130F (update_nitrogen)
00:36:07.219: Completed checkpoint id: 0x130F (update_nitrogen)
00:36:07.269: Started checkpoint id: 0x130B (update_usbc)
00:36:07.321: Completed checkpoint id: 0x130B (update_usbc)
00:36:07.371: Started checkpoint id: 0x131F (update_canary)
00:36:07.422: Completed checkpoint id: 0x131F (update_canary)
00:36:07.473: Started checkpoint id: 0x130D (update_savage)
00:36:07.524: <Restore Device 0x7f9603d65960>: operation 60 progress -1
00:36:07.524:  Updating biometrics sensor firmware
00:36:07.574: requested restore behavior: Erase
00:36:07.575:  Flash mode: Don't Retain User's Data While Flashing
00:36:07.626: requested restore behavior: Erase
00:36:07.628:  Flash mode: Don't Retain User's Data While Flashing
00:36:07.680: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: 
                     isRecovery = 0, entry = Savage,BA-Prod-Patch
00:36:07.819: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3
                     _22D64_Restore/Firmware/Savage/Savage.BA-Prod.fw
00:36:07.870: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/Savage/Savage.BA-Prod.fw
00:36:07.921: requested restore behavior: Erase
00:36:07.922:  Flash mode: Don't Retain User's Data While Flashing
00:36:07.972: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: 
                     isRecovery = 0, entry = Savage,BE-Prod-Patch
00:36:08.022: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.
                     3_22D64_Restore/Firmware/Savage/Savage.BE-Prod.fw
00:36:08.073: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/Savage/Savage.BE-Prod.fw
00:36:08.124: amai: _handleFirmwareUpdaterRequest: Savage updater has device-generated RestoreInfo
00:36:08.174: requested restore behavior: Erase
00:36:08.174:  Flash mode: Don't Retain User's Data While Flashing
00:36:08.225: repersonalization is ON for Savage updater
00:36:08.275: amai: AMAuthInstallUpdaterPersonalize: Adding AP fusing information to coprocessor TSS request.
00:36:08.326: amai: AMAuthInstallUpdaterCreateResponse: Updater local signing support: false
00:36:08.377: amai: AMAuthInstallRequestSendSyncWithHeader: SSO function returned NULL and no SSO token was provided, SSO disab
                     led.
00:36:08.430: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-request.plist
00:36:08.483: amai: tss_submit_job_with_retry: TSS Connection attempt 1 of 3.  (Will retry if TSS_ERR_SERVER_NOT_REACHABLE.)
00:36:08.535: ASR progress: Sending payload
00:36:08.586: amai: -[AMSupportStaticURLSession URLSession:didReceiveChallenge:completionHandler:]: Authentication challenge receiv
                     ed.  Method: NSURLAuthenticationMethodServerTrust
00:36:08.637: amai: AMAuthInstallRequestSendSyncWithHeader: received tss response (server version: 2.1.0)
00:36:08.687: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-response.plist
00:36:08.737: amai: AMAuthInstallUpdaterPersonalize: Stashing Savage ticket(s) in bundle (LoopInstance=(null))
00:36:08.788: Completed checkpoint id: 0x130D (update_savage)
00:36:08.838: Started checkpoint id: 0x1316 (update_appletcon)
00:36:08.889: <Restore Device 0x7f9603d65960>: operation 79 progress 0
00:36:08.939: <Restore Device 0x7f9603d65960>: operation 79 progress 100
00:36:08.990: Completed checkpoint id: 0x1316 (update_appletcon)
00:36:09.042: Started checkpoint id: 0x1326 (await_update_tcon)
00:36:09.092: Completed checkpoint id: 0x1326 (await_update_tcon)
00:36:09.144: Started checkpoint id: 0x1327 (await_update_orion)
00:36:09.200: Completed checkpoint id: 0x1327 (await_update_orion)
00:36:09.252: Started checkpoint id: 0x1328 (await_update_peppy)
00:36:09.302: Completed checkpoint id: 0x1328 (await_update_peppy)
00:36:09.353: Started checkpoint id: 0x1329 (await_update_nitrogen)
00:36:09.404: Completed checkpoint id: 0x1329 (await_update_nitrogen)
00:36:09.455: Started checkpoint id: 0x1325 (await_update_usbc)
00:36:09.506: <Restore Device 0x7f9603d65960>: operation 13 progress 3
00:36:09.506:  Sending file system via ASR 3%
00:36:09.557: ASR progress: Sending payload
00:36:09.607: <Restore Device 0x7f9603d65960>: operation 13 progress 4
00:36:09.607:  Sending file system via ASR 4%
00:36:09.658: <Restore Device 0x7f9603d65960>: operation 55 progress 100
00:36:09.709: <Restore Device 0x7f9603d65960>: operation 19 progress -1
00:36:09.709:  Updating baseband
00:36:09.760: requested restore behavior: Erase
00:36:09.760:  Flash mode: Don't Retain User's Data While Flashing
00:36:09.810: amai: AMAuthInstallBasebandSetParametersWithUpdaterOutput: baseband updater output: {
00:36:09.862: 00:36:09.914:     CertID = 524245983;
00:36:09.964:     ChipID = 104;
00:36:10.016: 00:36:10.067:     FusingStatus = 3;
00:36:10.117: 00:36:10.167:     VendorID = 2;
00:36:10.218:     attemptedToFuse = 0;
00:36:10.269:     done = 0;
00:36:10.320: }
00:36:10.371: amai: AMAuthInstallBasebandSetParametersWithUpdaterOutput: manifest dict not found
00:36:10.422: amai: _AMAuthInstallBasebandCheckForParameterChange: eUICC Param 0 unchanged
00:36:10.473: amai: _AMAuthInstallBasebandCheckForParameterChange: eUICC Param 1 unchanged
00:36:10.524: amai: _AMAuthInstallBasebandCheckForParameterChange: eUICC Param 2 unchanged
00:36:10.575: requested restore behavior: Erase
00:36:10.575:  Flash mode: Don't Retain User's Data While Flashing
00:36:10.625: requested variant: Erase
00:36:10.675: no override trust object found
00:36:10.726: requested restore behavior: Erase
00:36:10.727:  Flash mode: Don't Retain User's Data While Flashing
00:36:10.778: requested restore behavior: Erase
00:36:10.781:  Flash mode: Don't Retain User's Data While Flashing
00:36:10.831: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:36:10.884: personalizing: <AMAuthInstall 0x7f9603c43240>{ap=(personalize=YES d421ap ecid=0x1534a90c85802e, chipid=0x8030, bo
                     ardid=0x6, secDom=1, isProduction=YES, EPRO=YES, isSecure=YES, ESEC=YES, img4=YES, demotionPolicy=, managedBa
                     aCert=NO, slowRollBaaCert=NO, dpoc=(null)), bp=(personalize=YES, snum=0x1258e37c46f782f200000000, chipid=0x68, c
                     ertid=0x1f3f5bdf, nonce=0x9380a7826a99e2107212bcfba00e1a6fb6c02ed4), UserAuth=NO, iTunes=YES, server="https://g
                     s.apple.com:443", locale=Zh_cn, version="libauthinstall-1033.0.6", platform=mac/19H15/x86_64}
00:36:11.060: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:36:11.157: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:36:11.239: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreLogo to Manifest to personalize later
00:36:11.291: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreDeviceTree to Manifest to personalize later
00:36:11.341: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreKernelCache to Manifest to personalize later
00:36:11.393: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreRamDisk to Manifest to personalize later
00:36:11.444: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBEC to Manifest to personalize later
00:36:11.495: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBSS to Manifest to personalize later
00:36:11.547: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting KernelCache to Manifest to personalize later
00:36:11.598: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftap to Manifest to personalize later
00:36:11.650: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfta to Manifest to personalize later
00:36:11.700: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftsp to Manifest to personalize later
00:36:11.752: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfts to Manifest to personalize later
00:36:11.802: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,SystemVolumeCanonicalMetadata to Manifest to persona
                     lize later
00:36:11.853: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SystemVolume to Manifest to personalize later
00:36:11.904: amai: AMAuthInstallBasebandCreateMeasurements: Using set ChipID 0x00000068 to measure
00:36:11.905:  Requesting baseband SHSH via network
00:36:11.956: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA384 to hash PSI-Version
00:36:12.007: amai: AMAuthInstallRembrandtMeasureBootPSI: PSI-Version: version=0x98b1392
00:36:12.057: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA384 to hash RestorePSI-Version
00:36:12.108: amai: AMAuthInstallRembrandtMeasureBootPSI: RestorePSI-Version: version=0x98b1393
00:36:12.159: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA256 to hash PSI-Version
00:36:12.210: amai: AMAuthInstallRembrandtMeasureBootPSI: PSI-Version: version=0x98b1392
00:36:12.260: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA256 to hash RestorePSI-Version
00:36:12.346: amai: AMAuthInstallRembrandtMeasureBootPSI: RestorePSI-Version: version=0x98b1393
00:36:12.399: ASR progress: Sending payload
00:36:12.450: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 776 bytes]
00:36:12.502: amai: : 30 00 00 00 10 00 00 00 04 59 43 5a a7 dc 49 30
00:36:12.552: amai: : 0c 62 66 c5 0f c5 ed fa cf f0 18 08 c5 64 02 88
00:36:12.604: amai: : 58 b5 26 c6 6d 97 1a 77 00 09 76 29 3b 16 25 2f
00:36:12.654: amai: : bd 94 96 8c 0c b9 b7 f9 bf 9e 36 9e bc 1f 6b 2c
00:36:12.704: amai: : 0a 1d 9f 31 0b bf 3b b5 11 18 e5 7d ff f6 74 3c
00:36:12.756: amai: : 54 3b 53 0d ae 19 e3 6b 0a 68 da 9c d9 c0 43 f0
00:36:12.807: amai: : 1d 55 62 e4 0e 85 10 d8 82 cf f4 88 29 a6 c0 19
00:36:12.858: amai: : a4 78 d9 7c 3c 39 5f 9b 2d 34 93 c2 57 50 a9 25
00:36:12.908: amai: : ee eb 83 15 9a 25 07 52 6e 29 11 7c 93 6c e8 e6
00:36:12.959: amai: : fa 86 1e b3 8d 43 02 8f 81 26 11 37 d8 fc 28 54
00:36:13.010: amai: : 2d 9e 5e 5f b4 6e c8 50 9c b3 76 02 a9 ff 42 d7
00:36:13.060: amai: : 4b e9 b3 d5 b4 23 b2 ef 76 f2 b2 bc 00 d4 62 00
00:36:13.110: amai: : 80 11 19 c8 9b 0e 38 85 9d c1 07 44 28 1d 5b b2
00:36:13.161: amai: : 22 8f 01 61 a1 c2 72 50 4f 2e e6 d0 9a 09 a9 f8
00:36:13.212: amai: : d8 31 14 95 55 9f b0 44 cd 9f 30 f7 50 a8 6b 6a
00:36:13.262: amai: : 43 95 b4 1d 11 85 a9 12 52 99 dd e6 b2 b4 9b d2
00:36:13.313: amai: : d6 f3 2a 5b 13 38 f0 51 f8 6d 48 d0 23 12 80 c7
00:36:13.364: amai: : 08 aa ea ae 79 0d 2f 44 34 bd 1e 02 9b 19 f6 31
00:36:13.417: amai: : bb fa 2e 87 1c 04 ce c9 0e 47 3a f1 05 10 ad 5d
00:36:13.468: amai: : 2d 05 60 01 89 cc 98 d0 fc df 69 59 e5 eb 0f f8
00:36:13.519: amai: : 49 5f a8 f4 7b f8 83 8c 64 d0 58 82 16 93 ba 50
00:36:13.569: amai: : f1 dc 7a 15 2e 98 00 8d 60 22 1f 54 a7 7a b2 a9
00:36:13.619: amai: : b1 51 d4 4b f7 a3 5c 40 47 24 e3 79 32 0b 47 53
00:36:13.670: amai: : c1 c3 aa 70 5a b4 d6 f7 f2 a6 31 a9 63 d1 a1 96
00:36:13.720: amai: : 6a 16 a6 6b 08 2a 8b 18 61 81 43 d1 a3 90 d2 33
00:36:13.771: amai: : 64 49 cb 89 f2 65 fc b3 93 2f 87 5b 1b 0a 86 da
00:36:13.822: amai: : da dc 4b df 0a bc e6 55 81 04 a9 d5 39 49 3f 43
00:36:13.872: amai: : d9 1f 4c 09 82 62 21 b3 0a bc fc 44 d7 a7 85 fc
00:36:13.923: amai: : 96 9c 8b 19 d5 62 8d 38 2e 0d 93 c0 bb f5 98 c7
00:36:13.973: amai: : f5 f9 55 23 07 21 ab dc 85 3d 18 8c 04 35 1a aa
00:36:14.024: amai: : 2e 41 1f cb b4 97 81 43 b4 2f 79 d8 d9 f6 c3 87
00:36:14.074: amai: : 7b 4c 9d 95 83 ef da 24 0d f6 dd e8 95 44 aa 39
00:36:14.125: amai: : 0d 79 c5 19 60 06 97 cc 8c 4d 8f 67 20 fa c4 87
00:36:14.175: amai: : 2f f8 b5 46 9b 0a 1b 4c 9c a3 91 d6 17 30 f4 a0
00:36:14.226: amai: : 0b 0e 72 43 95 df a7 0c 78 c5 9a 1b c9 85 db 5b
00:36:14.276: amai: : 49 56 59 bd 87 e3 12 44 82 06 e7 26 7a dd 41 14
00:36:14.328: amai: : 3e 37 89 ab 65 1d ee 0d 5b 22 6a 86 54 b1 96 18
00:36:14.379: amai: : 4e 7a b5 58 86 dd a3 8d 7b e5 6c 3b ce ed 17 d1
00:36:14.430: amai: : c6 96 95 1c ef 1c 5f 5b 03 15 13 75 39 03 1c 39
00:36:14.480: amai: : 12 d6 e9 e0 66 76 6e f9 35 c6 ee 74 9d a4 9d 69
00:36:14.537: amai: : 70 cd 16 6d 95 74 1d 64 bc fd 5c 65 91 a6 f0 ca
00:36:14.587: amai: : fa bb 9c c0 3a 07 a2 35 9a c2 69 75 a2 04 dd 01
00:36:14.637: amai: : 2f f2 23 ca 32 2b 66 1a f9 e3 5a 10 85 ef 64 5f
00:36:14.688: amai: : 8a d1 8e 07 2e 92 cc 7f ca a7 b4 03 b9 cc 46 9a
00:36:14.739: amai: : ae 39 92 f8 b4 64 2f d5 4c 0a 77 2e fa 98 c3 b3
00:36:14.789: amai: : d8 5c b7 aa 52 1a 3a ff d8 ba 3a a3 8b 70 2f e9
00:36:14.841: amai: : ab 55 44 39 a0 9b 7d 8d c7 c2 03 f3 b5 7a de 9c
00:36:14.891: amai: : be ec b3 ea f0 9b ac 65 58 81 1d 19 ff f8 96 1e
00:36:14.943: amai: : 35 71 6d 0f 04 f7 65 c3
00:36:14.993: amai: : -----------------------------------------------
00:36:15.044: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 1976 bytes]
00:36:15.095: amai: : 30 00 00 00 29 00 00 00 63 15 1e cc c4 41 0e fb
00:36:15.145: amai: : 28 ab 8b 25 cd bc e8 f1 ec 60 e4 8d 2a fa bc a7
00:36:15.196: amai: : cd b4 e4 c2 e1 95 be 16 e2 1b b5 db db 4d fd 27
00:36:15.246: amai: : 7e ba d0 ad 4c 98 54 10 0b 61 31 d6 d6 bd 8d 46
00:36:15.297: amai: : 71 c5 eb 40 d3 f3 3f 92 7d 15 a0 a7 f2 f1 28 57
00:36:15.348: amai: : 1e 0a 16 27 aa dc d9 67 24 f0 ed ba 57 de 1e a0
00:36:15.399: amai: : 61 a2 e8 4a fa a0 92 6e 31 7a 72 d5 df 0a fc 2c
00:36:15.453: amai: : ff 5e 12 05 d2 4c 00 f5 1b c8 ac a5 1f a7 90 fd
00:36:15.503: amai: : 1d ee e4 9e 34 d0 9b 21 f4 f8 ff 74 89 bd f8 fc
00:36:15.554: amai: : 74 cf 62 19 79 da 63 e9 87 90 a2 84 6d 67 bf 9b
00:36:15.605: amai: : 59 4d ac f7 2f 65 bb 3a 5a 08 8c b9 12 47 09 03
00:36:15.656: amai: : 50 14 4a 98 dd 73 a9 f6 d8 ea 00 46 36 7d 14 58
00:36:15.706: amai: : c2 d9 8e 73 af f1 80 aa 55 70 64 89 91 c5 fe c2
00:36:15.757: amai: : 84 8c 86 1b 55 5e b4 e4 23 7e db f1 32 34 a8 c0
00:36:15.807: amai: : d0 fb 1f 96 e3 44 94 27 75 45 4d c1 fb 06 41 b2
00:36:15.858: amai: : 9e a6 05 dc da f8 c2 cd ec f9 b2 b3 34 63 41 8d
00:36:15.908: amai: : 15 e3 b9 39 6b a4 38 ed 60 47 ff 42 72 ac 86 fb
00:36:15.959: amai: : 45 70 60 53 ab e4 09 c6 7c 4f 64 ad 22 d9 8d 95
00:36:16.010: amai: : f3 4a 42 bf 0b 70 4d b5 0d 53 f2 4f 63 f0 dd 6f
00:36:16.061: amai: : 24 90 09 f2 63 0e 57 da 83 7d eb e1 88 4f 42 75
00:36:16.111: amai: : 68 ea 39 5b 3b 1d d7 64 a0 4d 8a 02 35 39 d4 2c
00:36:16.163: amai: : 2b 7c 45 9b 1f b7 47 6b 02 87 e0 70 12 31 61 58
00:36:16.213: amai: : 51 9d 66 74 24 b5 48 f0 3b ee 83 81 10 d3 e8 04
00:36:16.264: amai: : 03 69 f0 39 e4 53 87 f9 a1 1c 0f b8 4d 9f 93 9d
00:36:16.317: amai: : 3b 36 fe b1 27 44 7b 9e 5d 0f 67 a4 97 86 cc 5c
00:36:16.371: amai: : 46 72 e8 34 0e 3f 14 a1 f8 f4 bb 63 d4 ca 6e 32
00:36:16.421: amai: : 85 5e 34 81 bf 8c 20 ca 2c 40 6d 15 81 1f b3 1c
00:36:16.473: amai: : b8 4e 86 45 2b 1e 00 a5 0e 2c 86 51 0f f3 bb ba
00:36:16.524: amai: : 28 10 be f2 00 e8 31 29 0a e2 9f b9 60 42 6f e1
00:36:16.574: amai: : 34 bb 5e e7 29 c6 35 25 ef c7 76 b4 ae 8e ec f6
00:36:16.624: amai: : c5 f1 41 a3 6e 8c 04 66 ae 34 d0 ba 56 fc 5f 9c
00:36:16.675: amai: : fc 48 1a b0 27 cf e4 6b f8 a1 51 cf 14 ae 6f 04
00:36:16.725: amai: : ee c8 8e 3c 74 d8 f5 2c 4e 8f 7d bc cc eb f3 5a
00:36:16.777: amai: : 8a c0 20 2f 7d 8a 61 d0 b3 c4 96 ba 87 ae d8 a0
00:36:16.827: amai: : 5a fc 0c 89 15 42 8c d8 4f 24 6f 5b e2 33 84 75
00:36:16.878: amai: : 42 bd 3d 82 e8 ad b1 28 29 d1 80 96 4c 8b 98 6c
00:36:16.929: amai: : d1 7f 1b 98 28 70 b0 05 7f 33 a1 81 c4 be 25 3e
00:36:16.979: amai: : e4 0c e9 e7 84 27 af 94 1b a7 14 32 23 4e 7b 60
00:36:17.030: amai: : 36 59 8e 62 4e 50 07 80 5b ec d6 3a 5c 95 92 4a
00:36:17.080: amai: : 6b 5b 09 be be 0b da 69 96 64 b9 48 c8 cf 9c 28
00:36:17.130: amai: : be fe 06 2e 6c a1 92 f5 1a d1 8d 67 30 66 2e ac
00:36:17.182: amai: : 6b 6b b5 a8 73 04 15 54 34 f1 81 2b 6e b1 c4 0d
00:36:17.232: amai: : 53 3b 7f 51 ed 2f 04 76 ee 52 5a 5c fc 6d 4a 11
00:36:17.282: amai: : e0 8c dc 20 99 6f fc ff 3e df 68 4e fc 90 f3 6b
00:36:17.338: amai: : 76 88 5d c1 b3 db 17 ca db 9a a1 9a 28 d2 e7 e4
00:36:17.389: amai: : fd 4b 36 7d 18 d7 49 5d d1 9d c2 12 1e 65 74 93
00:36:17.439: amai: : ca 8b 23 c6 12 6b a4 20 62 92 b3 4e 4a 93 62 fd
00:36:17.491: amai: : 9b ea 26 a4 e7 89 7b 4b b5 66 7f 23 d8 a5 59 1d
00:36:17.541: amai: : be 45 01 40 26 5b 2f f2 bb 63 97 ba c6 96 ef 44
00:36:17.592: amai: : 9c ea 1f d0 d3 ef 1b 68 f2 5d 2a 58 6f e5 d5 c3
00:36:17.642: amai: : 28 c3 eb 48 ce 83 75 1e b5 1d dd 6f cc 5f 6b 95
00:36:17.693: amai: : 06 b4 90 25 84 f0 38 65 5d 6b 29 2e be ae b2 41
00:36:17.743: amai: : 7c be 65 31 ba eb a3 d2 c2 4b 57 a5 1c 4c a2 bd
00:36:17.793: amai: : 4d 59 83 be db 3e 31 be 7f a8 e0 63 a5 b0 7e 8d
00:36:17.844: amai: : 5b 58 8b 7f 5b 3c 43 0a 15 d3 d5 7b 6e 4c 82 d5
00:36:17.894: amai: : bb 05 42 45 7f 0b a5 d8 78 d2 e5 a8 71 19 b7 03
00:36:17.946: amai: : d5 f5 b4 f9 a5 27 f3 21 7b ff eb 12 25 ae 92 e8
00:36:17.996: amai: : dd b2 e2 89 cb 06 99 03 40 35 29 e2 91 5a 39 66
00:36:18.046: amai: : 9a a1 6c 1b 35 92 6b 34 30 39 9d d5 b5 29 a9 ca
00:36:18.098: amai: : e8 b7 a6 a6 84 f9 18 5c 69 ca 2f 11 d1 37 ed 49
00:36:18.148: amai: : e8 7f cc a4 c8 51 72 a8 45 63 ab 86 1f ed 36 e6
00:36:18.199: amai: : 99 76 dd 4c 49 ce c1 32 8d be 31 dd 19 da b5 4c
00:36:18.249: amai: : 55 87 df 27 a0 4f bb e0 47 15 d6 6a 72 8d 4e 6e
00:36:18.302: amai: : cb f3 a7 1d 63 c6 90 5c 80 04 6c 64 53 6c a6 7a
00:36:18.355: amai: : 15 81 fc ae 62 83 76 e0 bb 5d 02 d1 36 82 d0 6f
00:36:18.406: amai: : 2b a6 03 4b 20 33 81 f3 72 7c 8d b7 8b 1c da 46
00:36:18.456: amai: : d9 8d ff f9 48 6a fb a3 29 98 31 18 00 f2 2a d2
00:36:18.507: amai: : 7e bc 89 cc da c9 2d 87 2d 03 d2 11 15 e7 be 00
00:36:18.557: amai: : 86 7c ce 00 49 5b 8a 01 f9 bb dc 41 22 d5 29 e4
00:36:18.608: amai: : 09 69 15 be 06 6d 12 6d ed 2e b5 46 50 1d 6f 37
00:36:18.658: amai: : bc c6 8a c8 70 b9 a8 66 c3 e2 c1 6d da 75 22 4a
00:36:18.709: amai: : 68 43 58 f9 8d 00 a8 4d 15 98 a1 e2 7b 95 86 f7
00:36:18.760: amai: : 3b 45 7c 3d 12 a4 be 97 08 c3 ab 86 18 ad 61 20
00:36:18.811: amai: : c0 27 bc 7e 10 bc 6b 0e 8a 08 5c 5f 19 35 4c 89
00:36:18.861: amai: : 03 02 1e f3 cb 4b 0c 51 49 ef f9 ca cf 24 55 8d
00:36:18.912: amai: : 10 52 ee c2 bf b1 53 28 50 c0 fd 97 e3 8f cc f1
00:36:18.962: amai: : f1 0e f3 fc 84 ae d6 3e a7 40 e6 9c fe 7e c5 17
00:36:19.013: amai: : a3 5b ba 54 0a e5 14 09 9e 0a 45 dc b5 fb 2f 37
00:36:19.063: amai: : af 05 0e 16 08 4e c8 d8 c9 35 2d 32 f6 8f 31 03
00:36:19.114: amai: : ca e4 9b e9 0b bd 95 8a 4e d5 bb 57 a6 ec f7 6b
00:36:19.164: amai: : e4 ce b8 26 35 f7 2b 98 dd 86 8d 7e 05 5e d8 74
00:36:19.216: amai: : 43 49 12 a0 c4 98 7a c1 6f 6d b9 72 b2 88 b0 e4
00:36:19.267: amai: : 96 73 8c b1 65 28 88 ad ed 36 72 7c 44 d0 5f 20
00:36:19.319: amai: : 46 6e 73 7a fb 3e 1a 1d a6 57 f1 46 ae ff 1a 09
00:36:19.376: amai: : ce ab b9 7a 98 17 61 08 7b f0 51 c5 03 f9 eb 0e
00:36:19.427: amai: : a3 31 89 b7 4e 2f b1 8e ec 96 7a 48 eb f9 91 a5
00:36:19.477: amai: : 26 ba 7e 66 86 ff 6b 6c e6 59 40 1d 0b e3 0d 14
00:36:19.528: amai: : 90 86 9f 8d a7 e4 fe 91 53 73 b5 00 91 8f 59 54
00:36:19.578: amai: : 56 e4 d2 0c 08 5f 0b 7b 4b 56 82 ea a6 f4 ef e9
00:36:19.629: amai: : 4c 7e e0 42 4b e6 05 80 a7 11 a2 ed 96 09 3a 38
00:36:19.681: amai: : 4c c4 a8 0d 29 9e fa 38 26 9a 8a c0 06 47 24 ee
00:36:19.731: amai: : 50 c4 c5 3d ff c5 34 89 dc df 55 65 f2 cd f7 e9
00:36:19.781: amai: : ff d3 6e 76 96 a9 33 96 14 12 58 6b d9 5d 8e 2d
00:36:19.833: amai: : 85 ba a6 6e 56 0f 38 b4 ba 3d 3d 77 eb 69 2e 34
00:36:19.884: amai: : e1 30 23 86 90 fb 83 2f d2 64 6c 99 17 4a 8b b7
00:36:19.935: amai: : fc 39 71 f0 26 0d 6a b0 53 7c 52 2d d0 e6 83 ac
00:36:19.986: amai: : eb 42 e3 79 6b 7a ea 9d 1b 75 f8 6e 31 80 41 08
00:36:20.038: amai: : c9 be d4 aa 86 4d 4c ad 97 b9 37 80 f0 fd dd 91
00:36:20.090: amai: : 6e 46 b8 8e 93 b0 8a ec aa 54 b9 94 04 ab b0 6c
00:36:20.141: amai: : d4 71 0f 82 c4 e4 7d 19 c1 73 44 08 fa 8f 7d 0e
00:36:20.191: amai: : 08 08 2f 6a 6c 58 41 68 a9 df af c8 88 9b 10 7f
00:36:20.242: amai: : 33 7f d6 28 28 c8 79 7f a2 c8 40 13 c3 78 e5 a4
00:36:20.292: amai: : 20 75 7b 33 f8 a3 53 e1 19 93 4a 01 45 56 68 09
00:36:20.343: amai: : 1e 62 8e 7c f4 ee 9a 8d 99 ed 83 91 84 d3 77 d4
00:36:20.394: amai: : ed 05 a4 2b 81 d0 8b 96 98 b8 14 4f db a9 12 ed
00:36:20.444: amai: : 95 45 c0 06 f0 53 59 49 15 43 c2 6f 54 86 7a 2a
00:36:20.495: amai: : 9e 3c 1a 4c 34 46 70 97 19 8b fd 40 ca fe 5c fb
00:36:20.546: amai: : 7b 28 ea 3b 20 09 a2 50 3d 2f d0 5b ff 57 94 17
00:36:20.597: amai: : 5f 59 fa 35 52 ab 6d 3d e3 06 ba 06 38 d5 a0 7c
00:36:20.647: amai: : 80 18 d7 d6 ab 47 80 77 16 97 7d 50 3e 68 48 26
00:36:20.697: amai: : 2e 14 9c 16 43 ed fc 85 6f a3 11 78 29 b5 59 d8
00:36:20.748: amai: : bb e9 80 9d 26 5c 17 34 47 d0 c6 e7 d5 33 f2 5c
00:36:20.800: amai: : 15 4d 53 c7 91 39 c4 46 a7 26 b1 d5 7d 64 86 ee
00:36:20.850: amai: : 97 06 79 f4 03 f7 a6 66 26 b7 7a 34 ba 6d b0 54
00:36:20.900: amai: : da be b2 57 2c d2 96 fa 5a 22 1c 87 36 eb 29 4f
00:36:20.952: amai: : 1e 6e 87 27 b8 39 1a d3 e0 1f 20 f3 3e 41 13 21
00:36:21.003: amai: : 66 9c b3 ea 79 dd 36 e5 9e 15 aa 41 a7 c5 7d cb
00:36:21.054: amai: : 19 7e b6 57 0e 2a d7 e6 52 76 bd e9 1f 19 a5 f9
00:36:21.109: amai: : 27 90 76 45 7c 9a 96 0c d3 02 cc e2 de 6e 62 ff
00:36:21.159: amai: : 49 99 b6 1a a1 be 71 6c 3b 10 c4 12 dd 30 8a ab
00:36:21.211: amai: : 55 57 79 21 e7 c0 e3 80 75 47 0a eb 8e 14 b6 d4
00:36:21.264: amai: : 6f e1 7a 7e 5e 3e 8e 70 e8 8d fc 98 89 15 d9 0b
00:36:21.315: amai: : 79 7c 6f 49 99 df 72 d8 72 fc 5f 11 2c b7 f1 e7
00:36:21.366: amai: : b5 d7 d3 3b 3c 98 c2 28
00:36:21.416: amai: : -----------------------------------------------
00:36:21.467: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 104 bytes]
00:36:21.518: amai: : 30 00 00 00 02 00 00 00 79 fd 9f bc b9 03 2a b6
00:36:21.568: amai: : 83 f5 8f 50 37 10 33 6f 71 12 ae 84 98 16 36 8a
00:36:21.618: amai: : b0 8a 55 1f 9b a9 4f c0 d4 b2 30 e2 cf 71 8d e2
00:36:21.669: amai: : af 1d f3 ea d5 f0 78 84 cc fe 3d e5 78 a1 a3 ef
00:36:21.719: amai: : 2d f2 6e 55 1b fb 44 42 d9 aa 61 95 71 86 a9 9a
00:36:21.770: amai: : f7 ea 15 d9 ef d7 72 1f 9e 11 02 98 46 3f dd c6
00:36:21.820: amai: : 8d ec 29 fd 15 a4 5a d5
00:36:21.890: amai: : -----------------------------------------------
00:36:21.942: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 536 bytes]
00:36:21.992: amai: : 30 00 00 00 0b 00 00 00 c8 02 f2 25 ea 27 bd af
00:36:22.043: amai: : db 2d d5 07 60 b2 2b 9d 5f df b7 26 26 30 7c 59
00:36:22.094: amai: : 80 bc b1 40 42 61 93 f5 aa a1 02 19 97 5a 35 af
00:36:22.146: amai: : ba 56 af c0 d5 79 1b 42 1a c9 34 16 75 5f 91 c4
00:36:22.197: amai: : 72 09 ae 34 f8 84 2c c3 5c 2f 55 cf 2d 9e 66 cd
00:36:22.247: amai: : 7c 48 10 71 4b b5 c1 c9 de a1 24 cb 11 0d 85 c2
00:36:22.298: amai: : ff 8f 01 ab 1d d6 a2 97 1b d4 69 a9 54 fe de 3a
00:36:22.411: amai: : 83 7f 8c 64 a7 8e a5 0b 8f 93 88 3a 41 ae 2b 28
00:36:22.462: amai: : 15 49 40 d6 19 38 c3 f0 e2 1b 1e 6e 81 d0 07 73
00:36:22.513: amai: : 10 da 1b c3 65 d9 a2 db 8b a0 37 db 69 91 78 77
00:36:22.564: amai: : 5e fd 83 da 84 b1 2d bd f6 68 d5 db f4 c0 17 48
00:36:22.615: amai: : 52 cb 07 09 53 7e 68 06 b7 ee 91 18 c7 5a f1 a0
00:36:22.665: amai: : cb e5 10 55 ef 4c 04 dd 99 6a 0d 9c 37 62 04 73
00:36:22.716: amai: : 4f 37 00 df fe f8 27 20 40 e8 77 55 d3 71 ae a9
00:36:22.767: amai: : a9 8c c0 61 5b e0 06 d1 02 df bb d7 54 63 85 0e
00:36:22.828: amai: : 25 c5 50 79 60 c1 95 fe d6 98 58 88 d8 89 ff 3e
00:36:22.879: amai: : 5b 92 81 a6 82 7e fb 0c a0 d0 97 f4 32 0b 3a 7a
00:36:22.930: amai: : 4a ac d0 ee ff 81 cf 4d cc 34 30 07 d0 09 22 11
00:36:22.981: amai: : 1b 00 6b ae c9 b4 e7 96 a5 5e ff 0e 08 d0 c4 65
00:36:23.032: amai: : 93 e6 4e 4f f7 09 a0 e9 0e a7 b5 53 76 ef 5f f4
00:36:23.083: amai: : b6 86 e8 5b fd e7 04 81 58 a6 5c ff c0 6c 73 6a
00:36:23.133: amai: : da 00 d1 4f fe 15 5d 8b 9a 69 3c a6 71 6a cc 6b
00:36:23.184: amai: : 7c 75 63 d9 85 e7 71 5a ff ea 56 8a 61 56 52 5f
00:36:23.234: amai: : 6d ba ac b4 9e a0 a5 65 f2 2c ab 6e 9b 8e 79 9e
00:36:23.285: amai: : 6b f4 77 3b 46 54 84 1a e8 50 fa b6 93 5d 4b b9
00:36:23.335: amai: : 36 1d 19 46 fd 4b 56 ca 3d 86 ee 48 d8 6e 38 4c
00:36:23.386: amai: : 7e 90 0f 96 f3 6b de 22 c8 a2 d9 69 76 6a b6 a2
00:36:23.436: amai: : b9 a2 c1 9c f8 76 8d f9 00 d2 88 b7 ca 44 ae 1c
00:36:23.486: amai: : a9 6a 3d b5 d5 c5 75 63 9b 86 de 5e 29 cd 26 45
00:36:23.536: amai: : 3d af 7c 1a 54 a5 b0 f3 14 46 1d a8 1c ae ee de
00:36:23.587: amai: : ea 44 4f 21 0f 0a db fb d0 5e 60 5d f0 6f aa 90
00:36:23.638: amai: : ac 20 dd 3a fa bf 33 b0 21 86 42 06 4b fa 8f 00
00:36:23.689: amai: : 41 c7 8a e1 c1 51 92 9d 22 a6 4e c3 b1 f9 c4 d4
00:36:23.742: amai: : 04 ea ec e5 ac 35 8d 00
00:36:23.793: amai: : -----------------------------------------------
00:36:23.845: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 344 bytes]
00:36:23.897: amai: : 30 00 00 00 07 00 00 00 30 d7 6f 8c 4e bf ed ed
00:36:23.947: amai: : d7 4c a0 cb c0 57 14 ba 2a c6 b9 00 06 45 df 39
00:36:23.997: amai: : a7 4f 6a 6f f0 9f 7b d6 2e 83 90 7a 73 83 4e 2e
00:36:24.048: amai: : ec ec cf 7f 92 bf 99 73 c5 16 aa 8d 3b 45 7c 63
00:36:24.099: amai: : 6c 68 26 93 70 99 c0 d2 3a 13 f2 c3 70 1a 38 8b
00:36:24.149: amai: : 3c 8f e4 bc 20 73 28 1b 0c 44 62 61 03 69 88 4c
00:36:24.200: amai: : 4a ba ba 8e 97 b6 de be 9e 3e 94 54 7b 6b 5a a1
00:36:24.251: amai: : 19 38 30 a5 f3 00 2c cd b6 cf d9 54 77 29 f3 a7
00:36:24.301: amai: : 13 3c 74 94 3d 0b b0 59 6c 05 87 f1 97 37 8a d9
00:36:24.352: amai: : df 6c 74 e0 7c 23 d1 a2 c5 16 aa 8d 3b 45 7c 63
00:36:24.402: amai: : 6c 68 26 93 70 99 c0 d2 3a 13 f2 c3 70 1a 38 8b
00:36:24.453: amai: : 3c 8f e4 bc 20 73 28 1b 0c 44 62 61 03 69 88 4c
00:36:24.503: amai: : 4a ba ba 8e 97 b6 de be f7 f1 e2 e2 9b 40 85 92
00:36:24.554: amai: : e9 a4 f8 85 44 de 3c 3c d6 4a 69 14 88 e4 56 30
00:36:24.604: amai: : 16 d8 5a fc bc 5b fe 8e 23 bd e5 6a 05 fd 11 9c
00:36:24.654: amai: : 57 89 16 67 0c a1 bf 7b fc 11 28 49 0c 92 f9 7c
00:36:24.705: amai: : 76 8f 31 74 24 c5 c5 34 e7 25 f7 76 42 84 d1 cf
00:36:24.756: amai: : 1c 7b fe f6 9b a1 ee 9e 5d 5f e7 34 ed 6a af d5
00:36:24.806: amai: : 22 a9 13 7c df 74 88 f2 d1 3e 6a d9 0e ae 0a 61
00:36:24.861: amai: : 1f 8a 55 28 4b e5 11 3b c9 1c 3b 94 a2 c8 d7 21
00:36:24.921: amai: : 19 7d 98 c9 17 1d 63 76 67 ae 91 95 f2 14 69 24
00:36:24.976: amai: : 78 11 dc 12 73 ea 5d ac
00:36:25.027: amai: : -----------------------------------------------
00:36:25.082: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 680 bytes]
00:36:25.136: amai: : 30 00 00 00 0e 00 00 00 4f 01 10 c8 21 80 97 1f
00:36:25.186: amai: : b4 50 59 c9 b0 9b 6b ff 9a 72 a3 d3 3d 81 07 46
00:36:25.237: amai: : 9a 3d 2f 75 09 a8 6e ad 45 aa 81 a8 9d 9a 5e ef
00:36:25.287: amai: : 1f 0c 9e d4 97 8a d9 3a eb 9f f0 b1 47 aa b3 5d
00:36:25.339: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:36:25.389: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:36:25.444: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:36:25.495: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:36:25.545: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:36:25.596: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:36:25.646: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:36:25.697: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:36:25.748: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:36:25.799: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:36:25.849: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:36:25.900: amai: : 83 c8 b9 42 91 dd 6f aa f7 f0 da 04 88 29 b8 43
00:36:25.952: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:36:26.003: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:36:26.054: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:36:26.105: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:36:26.157: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:36:26.208: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:36:26.261: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:36:26.312: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:36:26.364: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:36:26.414: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:36:26.465: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:36:26.517: amai: : fc 40 88 5f 79 a0 20 89 14 a4 e9 8d e5 90 b2 b8
00:36:26.567: amai: : f9 12 c9 5a ef 91 70 49 52 2f 91 86 4b e3 fb 9d
00:36:26.618: amai: : c3 34 4a b1 31 53 fb 0e 00 04 4f 08 2b af f1 13
00:36:26.669: amai: : ff f7 37 ae e8 31 a6 b1 40 7e a2 ec 68 0c 19 11
00:36:26.720: amai: : 85 5a 2c 49 a9 16 33 e3 b9 4f 5c 0d cf bc 46 ae
00:36:26.771: amai: : 5f bc 42 3d b6 c1 08 bb eb 57 6b c6 33 da 5b a4
00:36:26.822: amai: : 2f e0 e8 cb 73 91 ca 28 49 a1 4b d4 f5 b4 a1 f4
00:36:26.873: amai: : 97 8a 93 9c 75 37 27 33 65 07 ab 50 37 66 30 a8
00:36:26.923: amai: : e5 01 e9 94 ff e0 7a eb 0d 2c 4d 58 22 5b e7 0a
00:36:26.974: amai: : 71 ec 46 a2 aa 04 8d 26 ef dc 34 80 82 fe 22 e8
00:36:27.028: amai: : 35 dd 1a 45 53 9a 56 c1 53 1b df c3 77 f5 9c 9e
00:36:27.079: amai: : c0 00 90 d7 34 a6 bc 17 b9 cd 73 70 e7 2a ae 31
00:36:27.131: amai: : 80 b7 c8 1e 50 b1 ce 72 9d e7 f6 bd cb 55 bd a8
00:36:27.183: amai: : 2f 7f 62 d4 7a 01 da 6a db f7 db ee 86 77 2b 6d
00:36:27.233: amai: : 1e 1e 67 ef 2c ac d7 63 56 f3 90 7d 96 86 2c 82
00:36:27.284: amai: : 2a 90 e0 ec 1f da 40 c3
00:36:27.335: amai: : -----------------------------------------------
00:36:27.386: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 248 bytes]
00:36:27.437: amai: : 30 00 00 00 05 00 00 00 57 ad 80 ac 99 4f 9c 5a
00:36:27.487: amai: : 2b 62 11 14 f4 fe 61 a3 6f 52 0a 61 bf 48 75 ff
00:36:27.538: amai: : ea de 86 71 17 88 8e d1 31 8e 9f 8b 66 e7 37 be
00:36:27.588: amai: : 5f fa 44 46 b8 5f 1a 2a 44 88 de db cd 51 3b bd
00:36:27.638: amai: : 23 6c 05 01 48 42 34 74 2c a3 14 c5 c7 d4 1f d6
00:36:27.689: amai: : 06 c7 e2 a9 a1 96 e2 76 0f 9f d7 83 2b ed 88 b3
00:36:27.739: amai: : 65 6f b6 0f ad 8d b4 f3 9f 85 a8 c7 d4 ad 4c 6c
00:36:27.790: amai: : b7 95 f1 2b 25 df 6e 70 d0 b6 02 59 54 9a a7 27
00:36:27.840: amai: : 79 fd e2 6f 13 83 f4 f7 42 ba 57 47 6e ba a7 0f
00:36:27.892: amai: : f3 9c b9 2f 23 eb 17 6e 0c fe 11 2c 08 c9 bc e3
00:36:27.943: amai: : 48 32 0a 23 4e b8 77 51 04 3f 4e ab 8e 7d 39 cf
00:36:27.996: amai: : ae 7b 5c 2f 1e 08 f2 e4 49 b5 90 c4 78 43 01 1c
00:36:28.047: amai: : b5 e8 73 c0 78 59 ed 49 d3 41 e0 3e 26 0e 5a 36
00:36:28.098: amai: : 76 29 21 ab 35 9e 00 6b 8d 92 9b fc 55 85 31 96
00:36:28.148: amai: : 61 c5 7b 3d 31 a5 c8 2b c4 fb 9c 9c fd b1 8e 89
00:36:28.199: amai: : 1b 2b e5 35 b7 2e fd 47
00:36:28.251: amai: : -----------------------------------------------
00:36:28.302: amai: BbfwReaderFindAndCopyFileData: failed to find bbfw item "vinyl/update/main/signedprofile.der": File error
00:36:28.352: amai: BbfwReaderFindAndCopyFileData: failed to find bbfw item "vinyl/update/gold/signedprofile.der": File error
00:36:28.403: amai: AMAuthInstallIsICE19BBGoldCertIDECDSA: GoldCertId: 1F3F5BDF
00:36:28.453: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BasebandFirmware to Manifest to personalize later
00:36:28.504: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting OS to Manifest to personalize later
00:36:28.555: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RecoveryMode to Manifest to personalize later
00:36:28.606: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Liquid to Manifest to personalize later
00:36:28.656: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow0 to Manifest to personalize later
00:36:28.707: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AVE to Manifest to personalize later
00:36:28.758: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ANE to Manifest to personalize later
00:36:28.808: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,HapticAssets to Manifest to personalize later
00:36:28.859: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryPlugin to Manifest to personalize later
00:36:28.914: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreSEP to Manifest to personalize later
00:36:28.965: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ISP to Manifest to personalize later
00:36:29.016: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SEP to Manifest to personalize later
00:36:29.067: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBoot to Manifest to personalize later
00:36:29.117: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreTrustCache to Manifest to personalize later
00:36:29.168: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet1 to Manifest to personalize later
00:36:29.219: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting DeviceTree to Manifest to personalize later
00:36:29.270: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AudioCodecFirmware to Manifest to personalize later
00:36:29.320: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting PMP to Manifest to personalize later
00:36:29.370: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LeapHaptics to Manifest to personalize later
00:36:29.421: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting StaticTrustCache to Manifest to personalize later
00:36:29.471: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging0 to Manifest to personalize later
00:36:29.522: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LLB to Manifest to personalize later
00:36:29.573: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow1 to Manifest to personalize later
00:36:29.624: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryFull to Manifest to personalize later
00:36:29.675: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AppleLogo to Manifest to personalize later
00:36:29.725: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SIO to Manifest to personalize later
00:36:29.776: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging1 to Manifest to personalize later
00:36:29.827: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting GFX to Manifest to personalize later
00:36:29.880: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AOP to Manifest to personalize later
00:36:29.931: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet0 to Manifest to personalize later
00:36:29.983: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting WCHFirmwareUpdater to Manifest to personalize later
00:36:30.034: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Multitouch to Manifest to personalize later
00:36:30.084: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbProvisioningManifestKeyHash = <CFDa
                     ta 0x7f9603c229d0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x238c5118db979840969fb4dba3ab2db3 ... 162
                     9e2a30e1df392}
00:36:30.134: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbActivationManifestKeyHash = <CFData
                     0x7f9603c6dda0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x1b41607650ebf11c6b39f41cb267dc64 ... 055803
                     e1ef81c870}
00:36:30.184: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbFDRSecurityKeyHash = <CFData 0x7f9
                     603c0e7c0 [0x7fff88086cc0]>{length = 0, capacity = 0, bytes = 0x}
00:36:30.235: amai: _AMAuthInstallBundleCreateServerRequestDictionary: ticketPath amai/apimg4ticket.der , withApTicket is False,  (!Tru
                     e && ( False || False))
00:36:30.285: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreLogo"
00:36:30.336: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreDeviceTree"
00:36:30.386: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreKernelCache"
00:36:30.437: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreRamDisk"
00:36:30.487: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "OSRamdisk" not part of manifest, skipping
00:36:30.539: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBEC"
00:36:30.590: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBSS"
00:36:30.642: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "KernelCache"
00:36:30.693: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftap" entry
00:36:30.743: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfta" entry
00:36:30.794: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftsp" entry
00:36:30.845: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfts" entry
00:36:30.898: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,SystemVolumeCanonicalMetadata"
00:36:30.949: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolumeCanonicalMetadata" not part of manif
                     est, skipping
00:36:31.002: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "BaseSystemVolume" not part of manifest, skipping
00:36:31.052: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,BaseSystemVolume" not part of manifest, skipping
00:36:31.103: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SystemVolume"
00:36:31.153: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolume" not part of manifest, skipping
00:36:31.204: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Ap,BaseSystemTrustCache" not part of manifest, skipping
00:36:31.255: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Diags" not part of manifest, skipping
00:36:31.305: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "CFELoader" not part of manifest, skipping
00:36:31.357: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "RBM" not part of manifest, skipping
00:36:31.408: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PHLEET" not part of manifest, skipping
00:36:31.458: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PERTOS" not part of manifest, skipping
00:36:31.509: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PEHammer" not part of manifest, skipping
00:36:31.559: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Alamo" not part of manifest, skipping
00:36:31.610: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "BasebandFirmware" has been previously personalized; ski
                     pping it
00:36:31.662: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "OS" entry
00:36:31.713: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RecoveryMode"
00:36:31.764: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Liquid"
00:36:31.816: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow0"
00:36:31.866: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AVE"
00:36:31.917: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ANE"
00:36:31.967: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,HapticAssets"
00:36:32.018: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryPlugin"
00:36:32.069: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreSEP"
00:36:32.120: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ISP"
00:36:32.171: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SEP"
00:36:32.221: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBoot"
00:36:32.272: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreTrustCache"
00:36:32.323: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet1"
00:36:32.373: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "DeviceTree"
00:36:32.424: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AudioCodecFirmware"
00:36:32.475: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "PMP"
00:36:32.525: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LeapHaptics"
00:36:32.576: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "StaticTrustCache"
00:36:32.626: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging0"
00:36:32.677: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LLB"
00:36:32.727: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow1"
00:36:32.777: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryFull"
00:36:32.828: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AppleLogo"
00:36:32.880: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SIO"
00:36:32.934: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging1"
00:36:32.984: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "GFX"
00:36:33.034: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AOP"
00:36:33.085: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet0"
00:36:33.135: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "WCHFirmwareUpdater"
00:36:33.187: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Multitouch"
00:36:33.238: amai: AMSupportPlatformCreateBufferFromNativeFilePath: open failed: No such file or directory
00:36:33.288: amai: AMSupportPlatformCreateBufferFromNativeFilePath: /usr/local/standalone/firmware/device_map.plist
00:36:33.339: amai: AMAuthInstallApCopyDeviceEntryFromDeviceMap: Failed to read devicemap from file:///usr/local/standalone/firmwa
                     re/device_map.plist
00:36:33.390: amai: AMAuthInstallApImg4ServerRequestAddUIDMode: Could not check if UID mode is required.
00:36:33.440: amai: _AddUpdaterTags: updater->requestTags is NULL
00:36:33.491: amai: _AddUpdaterTags: updater->requestTags is NULL
00:36:33.542: amai: _AMAuthInstallBundleCreateServerRequestDictionary: nothing to be done
00:36:33.592: Setting kAMRestoreOptionsiBootEANNuke.
00:36:33.643: <Restore Device 0x7f9603d65960>: operation 13 progress 5
00:36:33.643:  Sending file system via ASR 5%
00:36:33.695: sock  14: connected to  [usbmux_3]:49167
00:36:33.745: ASR progress: Sending payload
00:36:33.795: 2025-02-05 00:36:04.000 iTunesFlash[4281:8f03]: amai: AMAuthInstallBasebandHandleUpdaterStatus: commandAccepted:
                     YES
00:36:33.845: amai: AMAuthInstallBasebandHandleUpdaterStatus: outputDict: {
00:36:33.895: 00:36:33.946:     CertID = 524245983;
00:36:34.002:     ChipID = 104;
00:36:34.053: 00:36:34.104:     FusingStatus = 3;
00:36:34.155: 00:36:34.206:     VendorID = 2;
00:36:34.256:     attemptedToFuse = 0;
00:36:34.307:     done = 0;
00:36:34.357: }
00:36:34.407: sock  14: closed
00:36:34.458: requested restore behavior: Erase
00:36:34.458:  Flash mode: Don't Retain User's Data While Flashing
00:36:34.508: amai: AMAuthInstallBasebandSetParametersWithUpdaterOutput: baseband updater output: {
00:36:34.560: 00:36:34.611:     CertID = 524245983;
00:36:34.662:     ChipID = 104;
00:36:34.712: 00:36:34.763:     FusingStatus = 3;
00:36:34.813: 00:36:34.864:     VendorID = 2;
00:36:34.914:     attemptedToFuse = 0;
00:36:34.965:     done = 0;
00:36:35.018: }
00:36:35.069: amai: AMAuthInstallBasebandSetParametersWithUpdaterOutput: manifest dict not found
00:36:35.120: amai: _AMAuthInstallBasebandCheckForParameterChange: eUICC Param 0 unchanged
00:36:35.171: amai: _AMAuthInstallBasebandCheckForParameterChange: eUICC Param 1 unchanged
00:36:35.221: amai: _AMAuthInstallBasebandCheckForParameterChange: eUICC Param 2 unchanged
00:36:35.272: requested restore behavior: Erase
00:36:35.272:  Flash mode: Don't Retain User's Data While Flashing
00:36:35.323: requested variant: Erase
00:36:35.373: no override trust object found
00:36:35.424: requested restore behavior: Erase
00:36:35.424:  Flash mode: Don't Retain User's Data While Flashing
00:36:35.475: requested restore behavior: Erase
00:36:35.475:  Flash mode: Don't Retain User's Data While Flashing
00:36:35.525: amai: AMAuthInstallBundleFDRSupported: FDR is supported for this device
00:36:35.576: personalizing: <AMAuthInstall 0x7f9603c43240>{ap=(personalize=YES d421ap ecid=0x1534a90c85802e, chipid=0x8030, bo
                     ardid=0x6, secDom=1, isProduction=YES, EPRO=YES, isSecure=YES, ESEC=YES, img4=YES, demotionPolicy=, managedBa
                     aCert=NO, slowRollBaaCert=NO, dpoc=(null)), bp=(personalize=YES, snum=0x1258e37c46f782f200000000, chipid=0x68, c
                     ertid=0x1f3f5bdf, nonce=0x9380a7826a99e2107212bcfba00e1a6fb6c02ed4), UserAuth=NO, iTunes=YES, server="https://g
                     s.apple.com:443", locale=Zh_cn, version="libauthinstall-1033.0.6", platform=mac/19H15/x86_64}
00:36:35.626: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:36:35.677: amai: _AMAuthInstallBundleShouldPersonalizeOS: Personalize OS = Yes
00:36:35.727: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreLogo to Manifest to personalize later
00:36:35.779: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreDeviceTree to Manifest to personalize later
00:36:35.829: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreKernelCache to Manifest to personalize later
00:36:35.880: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreRamDisk to Manifest to personalize later
00:36:35.931: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBEC to Manifest to personalize later
00:36:35.982: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBSS to Manifest to personalize later
00:36:36.037: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting KernelCache to Manifest to personalize later
00:36:36.087: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftap to Manifest to personalize later
00:36:36.139: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfta to Manifest to personalize later
00:36:36.189: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ftsp to Manifest to personalize later
00:36:36.240: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting rfts to Manifest to personalize later
00:36:36.291: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,SystemVolumeCanonicalMetadata to Manifest to persona
                     lize later
00:36:36.341: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SystemVolume to Manifest to personalize later
00:36:36.393: amai: AMAuthInstallBasebandCreateMeasurements: Using set ChipID 0x00000068 to measure
00:36:36.393:  Requesting baseband SHSH via network
00:36:36.444: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA384 to hash PSI-Version
00:36:36.494: amai: AMAuthInstallRembrandtMeasureBootPSI: PSI-Version: version=0x98b1392
00:36:36.545: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA384 to hash RestorePSI-Version
00:36:36.595: amai: AMAuthInstallRembrandtMeasureBootPSI: RestorePSI-Version: version=0x98b1393
00:36:36.647: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA256 to hash PSI-Version
00:36:36.697: amai: AMAuthInstallRembrandtMeasureBootPSI: PSI-Version: version=0x98b1392
00:36:36.748: amai: AMAuthInstallRembrandtMeasureBootPSI: Using SHA256 to hash RestorePSI-Version
00:36:36.799: amai: AMAuthInstallRembrandtMeasureBootPSI: RestorePSI-Version: version=0x98b1393
00:36:36.854: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 776 bytes]
00:36:36.905: amai: : 30 00 00 00 10 00 00 00 04 59 43 5a a7 dc 49 30
00:36:36.956: amai: : 0c 62 66 c5 0f c5 ed fa cf f0 18 08 c5 64 02 88
00:36:37.006: amai: : 58 b5 26 c6 6d 97 1a 77 00 09 76 29 3b 16 25 2f
00:36:37.057: amai: : bd 94 96 8c 0c b9 b7 f9 bf 9e 36 9e bc 1f 6b 2c
00:36:37.108: amai: : 0a 1d 9f 31 0b bf 3b b5 11 18 e5 7d ff f6 74 3c
00:36:37.158: amai: : 54 3b 53 0d ae 19 e3 6b 0a 68 da 9c d9 c0 43 f0
00:36:37.208: amai: : 1d 55 62 e4 0e 85 10 d8 82 cf f4 88 29 a6 c0 19
00:36:37.260: amai: : a4 78 d9 7c 3c 39 5f 9b 2d 34 93 c2 57 50 a9 25
00:36:37.311: amai: : ee eb 83 15 9a 25 07 52 6e 29 11 7c 93 6c e8 e6
00:36:37.362: amai: : fa 86 1e b3 8d 43 02 8f 81 26 11 37 d8 fc 28 54
00:36:37.413: amai: : 2d 9e 5e 5f b4 6e c8 50 9c b3 76 02 a9 ff 42 d7
00:36:37.463: amai: : 4b e9 b3 d5 b4 23 b2 ef 76 f2 b2 bc 00 d4 62 00
00:36:37.515: amai: : 80 11 19 c8 9b 0e 38 85 9d c1 07 44 28 1d 5b b2
00:36:37.566: amai: : 22 8f 01 61 a1 c2 72 50 4f 2e e6 d0 9a 09 a9 f8
00:36:37.616: amai: : d8 31 14 95 55 9f b0 44 cd 9f 30 f7 50 a8 6b 6a
00:36:37.670: amai: : 43 95 b4 1d 11 85 a9 12 52 99 dd e6 b2 b4 9b d2
00:36:37.721: amai: : d6 f3 2a 5b 13 38 f0 51 f8 6d 48 d0 23 12 80 c7
00:36:37.772: amai: : 08 aa ea ae 79 0d 2f 44 34 bd 1e 02 9b 19 f6 31
00:36:37.823: amai: : bb fa 2e 87 1c 04 ce c9 0e 47 3a f1 05 10 ad 5d
00:36:37.875: amai: : 2d 05 60 01 89 cc 98 d0 fc df 69 59 e5 eb 0f f8
00:36:37.927: amai: : 49 5f a8 f4 7b f8 83 8c 64 d0 58 82 16 93 ba 50
00:36:37.978: amai: : f1 dc 7a 15 2e 98 00 8d 60 22 1f 54 a7 7a b2 a9
00:36:38.029: amai: : b1 51 d4 4b f7 a3 5c 40 47 24 e3 79 32 0b 47 53
00:36:38.080: amai: : c1 c3 aa 70 5a b4 d6 f7 f2 a6 31 a9 63 d1 a1 96
00:36:38.131: amai: : 6a 16 a6 6b 08 2a 8b 18 61 81 43 d1 a3 90 d2 33
00:36:38.181: amai: : 64 49 cb 89 f2 65 fc b3 93 2f 87 5b 1b 0a 86 da
00:36:38.232: amai: : da dc 4b df 0a bc e6 55 81 04 a9 d5 39 49 3f 43
00:36:38.282: amai: : d9 1f 4c 09 82 62 21 b3 0a bc fc 44 d7 a7 85 fc
00:36:38.332: amai: : 96 9c 8b 19 d5 62 8d 38 2e 0d 93 c0 bb f5 98 c7
00:36:38.383: amai: : f5 f9 55 23 07 21 ab dc 85 3d 18 8c 04 35 1a aa
00:36:38.433: amai: : 2e 41 1f cb b4 97 81 43 b4 2f 79 d8 d9 f6 c3 87
00:36:38.484: amai: : 7b 4c 9d 95 83 ef da 24 0d f6 dd e8 95 44 aa 39
00:36:38.539: amai: : 0d 79 c5 19 60 06 97 cc 8c 4d 8f 67 20 fa c4 87
00:36:38.590: amai: : 2f f8 b5 46 9b 0a 1b 4c 9c a3 91 d6 17 30 f4 a0
00:36:38.642: amai: : 0b 0e 72 43 95 df a7 0c 78 c5 9a 1b c9 85 db 5b
00:36:38.692: amai: : 49 56 59 bd 87 e3 12 44 82 06 e7 26 7a dd 41 14
00:36:38.743: amai: : 3e 37 89 ab 65 1d ee 0d 5b 22 6a 86 54 b1 96 18
00:36:38.794: amai: : 4e 7a b5 58 86 dd a3 8d 7b e5 6c 3b ce ed 17 d1
00:36:38.845: amai: : c6 96 95 1c ef 1c 5f 5b 03 15 13 75 39 03 1c 39
00:36:38.896: amai: : 12 d6 e9 e0 66 76 6e f9 35 c6 ee 74 9d a4 9d 69
00:36:38.947: amai: : 70 cd 16 6d 95 74 1d 64 bc fd 5c 65 91 a6 f0 ca
00:36:38.998: amai: : fa bb 9c c0 3a 07 a2 35 9a c2 69 75 a2 04 dd 01
00:36:39.049: amai: : 2f f2 23 ca 32 2b 66 1a f9 e3 5a 10 85 ef 64 5f
00:36:39.099: amai: : 8a d1 8e 07 2e 92 cc 7f ca a7 b4 03 b9 cc 46 9a
00:36:39.150: amai: : ae 39 92 f8 b4 64 2f d5 4c 0a 77 2e fa 98 c3 b3
00:36:39.200: amai: : d8 5c b7 aa 52 1a 3a ff d8 ba 3a a3 8b 70 2f e9
00:36:39.250: amai: : ab 55 44 39 a0 9b 7d 8d c7 c2 03 f3 b5 7a de 9c
00:36:39.301: amai: : be ec b3 ea f0 9b ac 65 58 81 1d 19 ff f8 96 1e
00:36:39.351: amai: : 35 71 6d 0f 04 f7 65 c3
00:36:39.403: amai: : -----------------------------------------------
00:36:39.456: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 1976 bytes]
00:36:39.506: amai: : 30 00 00 00 29 00 00 00 63 15 1e cc c4 41 0e fb
00:36:39.558: amai: : 28 ab 8b 25 cd bc e8 f1 ec 60 e4 8d 2a fa bc a7
00:36:39.610: amai: : cd b4 e4 c2 e1 95 be 16 e2 1b b5 db db 4d fd 27
00:36:39.660: amai: : 7e ba d0 ad 4c 98 54 10 0b 61 31 d6 d6 bd 8d 46
00:36:39.711: amai: : 71 c5 eb 40 d3 f3 3f 92 7d 15 a0 a7 f2 f1 28 57
00:36:39.761: amai: : 1e 0a 16 27 aa dc d9 67 24 f0 ed ba 57 de 1e a0
00:36:39.812: amai: : 61 a2 e8 4a fa a0 92 6e 31 7a 72 d5 df 0a fc 2c
00:36:39.862: amai: : ff 5e 12 05 d2 4c 00 f5 1b c8 ac a5 1f a7 90 fd
00:36:39.912: amai: : 1d ee e4 9e 34 d0 9b 21 f4 f8 ff 74 89 bd f8 fc
00:36:39.963: amai: : 74 cf 62 19 79 da 63 e9 87 90 a2 84 6d 67 bf 9b
00:36:40.013: amai: : 59 4d ac f7 2f 65 bb 3a 5a 08 8c b9 12 47 09 03
00:36:40.064: amai: : 50 14 4a 98 dd 73 a9 f6 d8 ea 00 46 36 7d 14 58
00:36:40.115: amai: : c2 d9 8e 73 af f1 80 aa 55 70 64 89 91 c5 fe c2
00:36:40.165: amai: : 84 8c 86 1b 55 5e b4 e4 23 7e db f1 32 34 a8 c0
00:36:40.216: amai: : d0 fb 1f 96 e3 44 94 27 75 45 4d c1 fb 06 41 b2
00:36:40.266: amai: : 9e a6 05 dc da f8 c2 cd ec f9 b2 b3 34 63 41 8d
00:36:40.317: amai: : 15 e3 b9 39 6b a4 38 ed 60 47 ff 42 72 ac 86 fb
00:36:40.369: amai: : 45 70 60 53 ab e4 09 c6 7c 4f 64 ad 22 d9 8d 95
00:36:40.423: amai: : f3 4a 42 bf 0b 70 4d b5 0d 53 f2 4f 63 f0 dd 6f
00:36:40.474: amai: : 24 90 09 f2 63 0e 57 da 83 7d eb e1 88 4f 42 75
00:36:40.524: amai: : 68 ea 39 5b 3b 1d d7 64 a0 4d 8a 02 35 39 d4 2c
00:36:40.576: amai: : 2b 7c 45 9b 1f b7 47 6b 02 87 e0 70 12 31 61 58
00:36:40.627: amai: : 51 9d 66 74 24 b5 48 f0 3b ee 83 81 10 d3 e8 04
00:36:40.678: amai: : 03 69 f0 39 e4 53 87 f9 a1 1c 0f b8 4d 9f 93 9d
00:36:40.729: amai: : 3b 36 fe b1 27 44 7b 9e 5d 0f 67 a4 97 86 cc 5c
00:36:40.779: amai: : 46 72 e8 34 0e 3f 14 a1 f8 f4 bb 63 d4 ca 6e 32
00:36:40.830: amai: : 85 5e 34 81 bf 8c 20 ca 2c 40 6d 15 81 1f b3 1c
00:36:40.881: amai: : b8 4e 86 45 2b 1e 00 a5 0e 2c 86 51 0f f3 bb ba
00:36:40.932: amai: : 28 10 be f2 00 e8 31 29 0a e2 9f b9 60 42 6f e1
00:36:40.982: amai: : 34 bb 5e e7 29 c6 35 25 ef c7 76 b4 ae 8e ec f6
00:36:41.034: amai: : c5 f1 41 a3 6e 8c 04 66 ae 34 d0 ba 56 fc 5f 9c
00:36:41.085: amai: : fc 48 1a b0 27 cf e4 6b f8 a1 51 cf 14 ae 6f 04
00:36:41.137: amai: : ee c8 8e 3c 74 d8 f5 2c 4e 8f 7d bc cc eb f3 5a
00:36:41.190: amai: : 8a c0 20 2f 7d 8a 61 d0 b3 c4 96 ba 87 ae d8 a0
00:36:41.241: amai: : 5a fc 0c 89 15 42 8c d8 4f 24 6f 5b e2 33 84 75
00:36:41.292: amai: : 42 bd 3d 82 e8 ad b1 28 29 d1 80 96 4c 8b 98 6c
00:36:41.343: amai: : d1 7f 1b 98 28 70 b0 05 7f 33 a1 81 c4 be 25 3e
00:36:41.427: amai: : e4 0c e9 e7 84 27 af 94 1b a7 14 32 23 4e 7b 60
00:36:41.478: amai: : 36 59 8e 62 4e 50 07 80 5b ec d6 3a 5c 95 92 4a
00:36:41.529: amai: : 6b 5b 09 be be 0b da 69 96 64 b9 48 c8 cf 9c 28
00:36:41.580: amai: : be fe 06 2e 6c a1 92 f5 1a d1 8d 67 30 66 2e ac
00:36:41.630: amai: : 6b 6b b5 a8 73 04 15 54 34 f1 81 2b 6e b1 c4 0d
00:36:41.682: amai: : 53 3b 7f 51 ed 2f 04 76 ee 52 5a 5c fc 6d 4a 11
00:36:41.733: amai: : e0 8c dc 20 99 6f fc ff 3e df 68 4e fc 90 f3 6b
00:36:41.783: amai: : 76 88 5d c1 b3 db 17 ca db 9a a1 9a 28 d2 e7 e4
00:36:41.834: amai: : fd 4b 36 7d 18 d7 49 5d d1 9d c2 12 1e 65 74 93
00:36:41.885: amai: : ca 8b 23 c6 12 6b a4 20 62 92 b3 4e 4a 93 62 fd
00:36:41.936: amai: : 9b ea 26 a4 e7 89 7b 4b b5 66 7f 23 d8 a5 59 1d
00:36:41.988: amai: : be 45 01 40 26 5b 2f f2 bb 63 97 ba c6 96 ef 44
00:36:42.043: amai: : 9c ea 1f d0 d3 ef 1b 68 f2 5d 2a 58 6f e5 d5 c3
00:36:42.094: amai: : 28 c3 eb 48 ce 83 75 1e b5 1d dd 6f cc 5f 6b 95
00:36:42.145: amai: : 06 b4 90 25 84 f0 38 65 5d 6b 29 2e be ae b2 41
00:36:42.195: amai: : 7c be 65 31 ba eb a3 d2 c2 4b 57 a5 1c 4c a2 bd
00:36:42.246: amai: : 4d 59 83 be db 3e 31 be 7f a8 e0 63 a5 b0 7e 8d
00:36:42.296: amai: : 5b 58 8b 7f 5b 3c 43 0a 15 d3 d5 7b 6e 4c 82 d5
00:36:42.346: amai: : bb 05 42 45 7f 0b a5 d8 78 d2 e5 a8 71 19 b7 03
00:36:42.396: amai: : d5 f5 b4 f9 a5 27 f3 21 7b ff eb 12 25 ae 92 e8
00:36:42.448: amai: : dd b2 e2 89 cb 06 99 03 40 35 29 e2 91 5a 39 66
00:36:42.498: amai: : 9a a1 6c 1b 35 92 6b 34 30 39 9d d5 b5 29 a9 ca
00:36:42.548: amai: : e8 b7 a6 a6 84 f9 18 5c 69 ca 2f 11 d1 37 ed 49
00:36:42.600: amai: : e8 7f cc a4 c8 51 72 a8 45 63 ab 86 1f ed 36 e6
00:36:42.650: amai: : 99 76 dd 4c 49 ce c1 32 8d be 31 dd 19 da b5 4c
00:36:42.701: amai: : 55 87 df 27 a0 4f bb e0 47 15 d6 6a 72 8d 4e 6e
00:36:42.752: amai: : cb f3 a7 1d 63 c6 90 5c 80 04 6c 64 53 6c a6 7a
00:36:42.802: amai: : 15 81 fc ae 62 83 76 e0 bb 5d 02 d1 36 82 d0 6f
00:36:42.852: amai: : 2b a6 03 4b 20 33 81 f3 72 7c 8d b7 8b 1c da 46
00:36:42.903: amai: : d9 8d ff f9 48 6a fb a3 29 98 31 18 00 f2 2a d2
00:36:42.953: amai: : 7e bc 89 cc da c9 2d 87 2d 03 d2 11 15 e7 be 00
00:36:43.009: amai: : 86 7c ce 00 49 5b 8a 01 f9 bb dc 41 22 d5 29 e4
00:36:43.059: amai: : 09 69 15 be 06 6d 12 6d ed 2e b5 46 50 1d 6f 37
00:36:43.110: amai: : bc c6 8a c8 70 b9 a8 66 c3 e2 c1 6d da 75 22 4a
00:36:43.160: amai: : 68 43 58 f9 8d 00 a8 4d 15 98 a1 e2 7b 95 86 f7
00:36:43.211: amai: : 3b 45 7c 3d 12 a4 be 97 08 c3 ab 86 18 ad 61 20
00:36:43.271: amai: : c0 27 bc 7e 10 bc 6b 0e 8a 08 5c 5f 19 35 4c 89
00:36:43.337: amai: : 03 02 1e f3 cb 4b 0c 51 49 ef f9 ca cf 24 55 8d
00:36:43.393: amai: : 10 52 ee c2 bf b1 53 28 50 c0 fd 97 e3 8f cc f1
00:36:43.443: amai: : f1 0e f3 fc 84 ae d6 3e a7 40 e6 9c fe 7e c5 17
00:36:43.493: amai: : a3 5b ba 54 0a e5 14 09 9e 0a 45 dc b5 fb 2f 37
00:36:43.544: amai: : af 05 0e 16 08 4e c8 d8 c9 35 2d 32 f6 8f 31 03
00:36:43.595: amai: : ca e4 9b e9 0b bd 95 8a 4e d5 bb 57 a6 ec f7 6b
00:36:43.645: amai: : e4 ce b8 26 35 f7 2b 98 dd 86 8d 7e 05 5e d8 74
00:36:43.697: amai: : 43 49 12 a0 c4 98 7a c1 6f 6d b9 72 b2 88 b0 e4
00:36:43.748: amai: : 96 73 8c b1 65 28 88 ad ed 36 72 7c 44 d0 5f 20
00:36:43.799: amai: : 46 6e 73 7a fb 3e 1a 1d a6 57 f1 46 ae ff 1a 09
00:36:43.849: amai: : ce ab b9 7a 98 17 61 08 7b f0 51 c5 03 f9 eb 0e
00:36:43.900: amai: : a3 31 89 b7 4e 2f b1 8e ec 96 7a 48 eb f9 91 a5
00:36:43.950: amai: : 26 ba 7e 66 86 ff 6b 6c e6 59 40 1d 0b e3 0d 14
00:36:44.001: amai: : 90 86 9f 8d a7 e4 fe 91 53 73 b5 00 91 8f 59 54
00:36:44.053: amai: : 56 e4 d2 0c 08 5f 0b 7b 4b 56 82 ea a6 f4 ef e9
00:36:44.103: amai: : 4c 7e e0 42 4b e6 05 80 a7 11 a2 ed 96 09 3a 38
00:36:44.154: amai: : 4c c4 a8 0d 29 9e fa 38 26 9a 8a c0 06 47 24 ee
00:36:44.204: amai: : 50 c4 c5 3d ff c5 34 89 dc df 55 65 f2 cd f7 e9
00:36:44.255: amai: : ff d3 6e 76 96 a9 33 96 14 12 58 6b d9 5d 8e 2d
00:36:44.310: amai: : 85 ba a6 6e 56 0f 38 b4 ba 3d 3d 77 eb 69 2e 34
00:36:44.361: amai: : e1 30 23 86 90 fb 83 2f d2 64 6c 99 17 4a 8b b7
00:36:44.415: amai: : fc 39 71 f0 26 0d 6a b0 53 7c 52 2d d0 e6 83 ac
00:36:44.465: amai: : eb 42 e3 79 6b 7a ea 9d 1b 75 f8 6e 31 80 41 08
00:36:44.516: amai: : c9 be d4 aa 86 4d 4c ad 97 b9 37 80 f0 fd dd 91
00:36:44.568: amai: : 6e 46 b8 8e 93 b0 8a ec aa 54 b9 94 04 ab b0 6c
00:36:44.618: amai: : d4 71 0f 82 c4 e4 7d 19 c1 73 44 08 fa 8f 7d 0e
00:36:44.668: amai: : 08 08 2f 6a 6c 58 41 68 a9 df af c8 88 9b 10 7f
00:36:44.719: amai: : 33 7f d6 28 28 c8 79 7f a2 c8 40 13 c3 78 e5 a4
00:36:44.770: amai: : 20 75 7b 33 f8 a3 53 e1 19 93 4a 01 45 56 68 09
00:36:44.821: amai: : 1e 62 8e 7c f4 ee 9a 8d 99 ed 83 91 84 d3 77 d4
00:36:44.871: amai: : ed 05 a4 2b 81 d0 8b 96 98 b8 14 4f db a9 12 ed
00:36:44.921: amai: : 95 45 c0 06 f0 53 59 49 15 43 c2 6f 54 86 7a 2a
00:36:44.973: amai: : 9e 3c 1a 4c 34 46 70 97 19 8b fd 40 ca fe 5c fb
00:36:45.027: amai: : 7b 28 ea 3b 20 09 a2 50 3d 2f d0 5b ff 57 94 17
00:36:45.078: amai: : 5f 59 fa 35 52 ab 6d 3d e3 06 ba 06 38 d5 a0 7c
00:36:45.129: amai: : 80 18 d7 d6 ab 47 80 77 16 97 7d 50 3e 68 48 26
00:36:45.179: amai: : 2e 14 9c 16 43 ed fc 85 6f a3 11 78 29 b5 59 d8
00:36:45.230: amai: : bb e9 80 9d 26 5c 17 34 47 d0 c6 e7 d5 33 f2 5c
00:36:45.281: amai: : 15 4d 53 c7 91 39 c4 46 a7 26 b1 d5 7d 64 86 ee
00:36:45.332: amai: : 97 06 79 f4 03 f7 a6 66 26 b7 7a 34 ba 6d b0 54
00:36:45.384: amai: : da be b2 57 2c d2 96 fa 5a 22 1c 87 36 eb 29 4f
00:36:45.434: amai: : 1e 6e 87 27 b8 39 1a d3 e0 1f 20 f3 3e 41 13 21
00:36:45.486: amai: : 66 9c b3 ea 79 dd 36 e5 9e 15 aa 41 a7 c5 7d cb
00:36:45.537: amai: : 19 7e b6 57 0e 2a d7 e6 52 76 bd e9 1f 19 a5 f9
00:36:45.587: amai: : 27 90 76 45 7c 9a 96 0c d3 02 cc e2 de 6e 62 ff
00:36:45.637: amai: : 49 99 b6 1a a1 be 71 6c 3b 10 c4 12 dd 30 8a ab
00:36:45.689: amai: : 55 57 79 21 e7 c0 e3 80 75 47 0a eb 8e 14 b6 d4
00:36:45.740: amai: : 6f e1 7a 7e 5e 3e 8e 70 e8 8d fc 98 89 15 d9 0b
00:36:45.795: amai: : 79 7c 6f 49 99 df 72 d8 72 fc 5f 11 2c b7 f1 e7
00:36:45.846: amai: : b5 d7 d3 3b 3c 98 c2 28
00:36:45.896: amai: : -----------------------------------------------
00:36:45.947: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 104 bytes]
00:36:45.999: amai: : 30 00 00 00 02 00 00 00 79 fd 9f bc b9 03 2a b6
00:36:46.050: amai: : 83 f5 8f 50 37 10 33 6f 71 12 ae 84 98 16 36 8a
00:36:46.100: amai: : b0 8a 55 1f 9b a9 4f c0 d4 b2 30 e2 cf 71 8d e2
00:36:46.151: amai: : af 1d f3 ea d5 f0 78 84 cc fe 3d e5 78 a1 a3 ef
00:36:46.202: amai: : 2d f2 6e 55 1b fb 44 42 d9 aa 61 95 71 86 a9 9a
00:36:46.252: amai: : f7 ea 15 d9 ef d7 72 1f 9e 11 02 98 46 3f dd c6
00:36:46.303: amai: : 8d ec 29 fd 15 a4 5a d5
00:36:46.353: amai: : -----------------------------------------------
00:36:46.403: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 536 bytes]
00:36:46.454: amai: : 30 00 00 00 0b 00 00 00 c8 02 f2 25 ea 27 bd af
00:36:46.504: amai: : db 2d d5 07 60 b2 2b 9d 5f df b7 26 26 30 7c 59
00:36:46.554: amai: : 80 bc b1 40 42 61 93 f5 aa a1 02 19 97 5a 35 af
00:36:46.605: amai: : ba 56 af c0 d5 79 1b 42 1a c9 34 16 75 5f 91 c4
00:36:46.655: amai: : 72 09 ae 34 f8 84 2c c3 5c 2f 55 cf 2d 9e 66 cd
00:36:46.706: amai: : 7c 48 10 71 4b b5 c1 c9 de a1 24 cb 11 0d 85 c2
00:36:46.756: amai: : ff 8f 01 ab 1d d6 a2 97 1b d4 69 a9 54 fe de 3a
00:36:46.807: amai: : 83 7f 8c 64 a7 8e a5 0b 8f 93 88 3a 41 ae 2b 28
00:36:46.858: amai: : 15 49 40 d6 19 38 c3 f0 e2 1b 1e 6e 81 d0 07 73
00:36:46.911: amai: : 10 da 1b c3 65 d9 a2 db 8b a0 37 db 69 91 78 77
00:36:46.962: amai: : 5e fd 83 da 84 b1 2d bd f6 68 d5 db f4 c0 17 48
00:36:47.013: amai: : 52 cb 07 09 53 7e 68 06 b7 ee 91 18 c7 5a f1 a0
00:36:47.063: amai: : cb e5 10 55 ef 4c 04 dd 99 6a 0d 9c 37 62 04 73
00:36:47.114: amai: : 4f 37 00 df fe f8 27 20 40 e8 77 55 d3 71 ae a9
00:36:47.165: amai: : a9 8c c0 61 5b e0 06 d1 02 df bb d7 54 63 85 0e
00:36:47.216: amai: : 25 c5 50 79 60 c1 95 fe d6 98 58 88 d8 89 ff 3e
00:36:47.267: amai: : 5b 92 81 a6 82 7e fb 0c a0 d0 97 f4 32 0b 3a 7a
00:36:47.318: amai: : 4a ac d0 ee ff 81 cf 4d cc 34 30 07 d0 09 22 11
00:36:47.371: amai: : 1b 00 6b ae c9 b4 e7 96 a5 5e ff 0e 08 d0 c4 65
00:36:47.421: amai: : 93 e6 4e 4f f7 09 a0 e9 0e a7 b5 53 76 ef 5f f4
00:36:47.472: amai: : b6 86 e8 5b fd e7 04 81 58 a6 5c ff c0 6c 73 6a
00:36:47.522: amai: : da 00 d1 4f fe 15 5d 8b 9a 69 3c a6 71 6a cc 6b
00:36:47.572: amai: : 7c 75 63 d9 85 e7 71 5a ff ea 56 8a 61 56 52 5f
00:36:47.623: amai: : 6d ba ac b4 9e a0 a5 65 f2 2c ab 6e 9b 8e 79 9e
00:36:47.674: amai: : 6b f4 77 3b 46 54 84 1a e8 50 fa b6 93 5d 4b b9
00:36:47.725: amai: : 36 1d 19 46 fd 4b 56 ca 3d 86 ee 48 d8 6e 38 4c
00:36:47.779: amai: : 7e 90 0f 96 f3 6b de 22 c8 a2 d9 69 76 6a b6 a2
00:36:47.830: amai: : b9 a2 c1 9c f8 76 8d f9 00 d2 88 b7 ca 44 ae 1c
00:36:47.880: amai: : a9 6a 3d b5 d5 c5 75 63 9b 86 de 5e 29 cd 26 45
00:36:47.931: amai: : 3d af 7c 1a 54 a5 b0 f3 14 46 1d a8 1c ae ee de
00:36:47.982: amai: : ea 44 4f 21 0f 0a db fb d0 5e 60 5d f0 6f aa 90
00:36:48.033: amai: : ac 20 dd 3a fa bf 33 b0 21 86 42 06 4b fa 8f 00
00:36:48.083: amai: : 41 c7 8a e1 c1 51 92 9d 22 a6 4e c3 b1 f9 c4 d4
00:36:48.134: amai: : 04 ea ec e5 ac 35 8d 00
00:36:48.185: amai: : -----------------------------------------------
00:36:48.235: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 344 bytes]
00:36:48.286: amai: : 30 00 00 00 07 00 00 00 30 d7 6f 8c 4e bf ed ed
00:36:48.337: amai: : d7 4c a0 cb c0 57 14 ba 2a c6 b9 00 06 45 df 39
00:36:48.388: amai: : a7 4f 6a 6f f0 9f 7b d6 2e 83 90 7a 73 83 4e 2e
00:36:48.439: amai: : ec ec cf 7f 92 bf 99 73 c5 16 aa 8d 3b 45 7c 63
00:36:48.489: amai: : 6c 68 26 93 70 99 c0 d2 3a 13 f2 c3 70 1a 38 8b
00:36:48.539: amai: : 3c 8f e4 bc 20 73 28 1b 0c 44 62 61 03 69 88 4c
00:36:48.590: amai: : 4a ba ba 8e 97 b6 de be 9e 3e 94 54 7b 6b 5a a1
00:36:48.640: amai: : 19 38 30 a5 f3 00 2c cd b6 cf d9 54 77 29 f3 a7
00:36:48.691: amai: : 13 3c 74 94 3d 0b b0 59 6c 05 87 f1 97 37 8a d9
00:36:48.742: amai: : df 6c 74 e0 7c 23 d1 a2 c5 16 aa 8d 3b 45 7c 63
00:36:48.796: amai: : 6c 68 26 93 70 99 c0 d2 3a 13 f2 c3 70 1a 38 8b
00:36:48.846: amai: : 3c 8f e4 bc 20 73 28 1b 0c 44 62 61 03 69 88 4c
00:36:48.897: amai: : 4a ba ba 8e 97 b6 de be f7 f1 e2 e2 9b 40 85 92
00:36:48.948: amai: : e9 a4 f8 85 44 de 3c 3c d6 4a 69 14 88 e4 56 30
00:36:48.998: amai: : 16 d8 5a fc bc 5b fe 8e 23 bd e5 6a 05 fd 11 9c
00:36:49.049: amai: : 57 89 16 67 0c a1 bf 7b fc 11 28 49 0c 92 f9 7c
00:36:49.099: amai: : 76 8f 31 74 24 c5 c5 34 e7 25 f7 76 42 84 d1 cf
00:36:49.150: amai: : 1c 7b fe f6 9b a1 ee 9e 5d 5f e7 34 ed 6a af d5
00:36:49.200: amai: : 22 a9 13 7c df 74 88 f2 d1 3e 6a d9 0e ae 0a 61
00:36:49.251: amai: : 1f 8a 55 28 4b e5 11 3b c9 1c 3b 94 a2 c8 d7 21
00:36:49.302: amai: : 19 7d 98 c9 17 1d 63 76 67 ae 91 95 f2 14 69 24
00:36:49.352: amai: : 78 11 dc 12 73 ea 5d ac
00:36:49.403: amai: : -----------------------------------------------
00:36:49.453: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 680 bytes]
00:36:49.503: amai: : 30 00 00 00 0e 00 00 00 4f 01 10 c8 21 80 97 1f
00:36:49.555: amai: : b4 50 59 c9 b0 9b 6b ff 9a 72 a3 d3 3d 81 07 46
00:36:49.606: amai: : 9a 3d 2f 75 09 a8 6e ad 45 aa 81 a8 9d 9a 5e ef
00:36:49.656: amai: : 1f 0c 9e d4 97 8a d9 3a eb 9f f0 b1 47 aa b3 5d
00:36:49.707: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:36:49.758: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:36:49.809: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:36:49.859: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:36:49.909: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:36:49.960: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:36:50.015: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:36:50.066: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:36:50.117: amai: : 83 c8 b9 42 91 dd 6f aa eb 9f f0 b1 47 aa b3 5d
00:36:50.168: amai: : 49 ba fa f7 60 58 71 c9 8a 14 91 93 de 05 30 76
00:36:50.218: amai: : 21 7a ae 23 85 9e 07 f2 e1 9d f1 c8 54 65 3f c7
00:36:50.269: amai: : 83 c8 b9 42 91 dd 6f aa f7 f0 da 04 88 29 b8 43
00:36:50.321: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:36:50.372: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:36:50.422: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:36:50.473: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:36:50.523: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:36:50.574: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:36:50.625: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:36:50.676: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:36:50.726: amai: : fc 40 88 5f 79 a0 20 89 f7 f0 da 04 88 29 b8 43
00:36:50.777: amai: : 31 93 f8 b1 b0 22 19 44 64 67 59 a1 41 98 98 3c
00:36:50.828: amai: : e3 b7 a6 3d 3d 1b c7 2b 5d a5 f1 c4 ee 1d bd c7
00:36:50.881: amai: : fc 40 88 5f 79 a0 20 89 14 a4 e9 8d e5 90 b2 b8
00:36:50.931: amai: : f9 12 c9 5a ef 91 70 49 52 2f 91 86 4b e3 fb 9d
00:36:50.983: amai: : c3 34 4a b1 31 53 fb 0e 00 04 4f 08 2b af f1 13
00:36:51.034: amai: : ff f7 37 ae e8 31 a6 b1 40 7e a2 ec 68 0c 19 11
00:36:51.086: amai: : 85 5a 2c 49 a9 16 33 e3 b9 4f 5c 0d cf bc 46 ae
00:36:51.137: amai: : 5f bc 42 3d b6 c1 08 bb eb 57 6b c6 33 da 5b a4
00:36:51.187: amai: : 2f e0 e8 cb 73 91 ca 28 49 a1 4b d4 f5 b4 a1 f4
00:36:51.238: amai: : 97 8a 93 9c 75 37 27 33 65 07 ab 50 37 66 30 a8
00:36:51.289: amai: : e5 01 e9 94 ff e0 7a eb 0d 2c 4d 58 22 5b e7 0a
00:36:51.339: amai: : 71 ec 46 a2 aa 04 8d 26 ef dc 34 80 82 fe 22 e8
00:36:51.390: amai: : 35 dd 1a 45 53 9a 56 c1 53 1b df c3 77 f5 9c 9e
00:36:51.442: amai: : c0 00 90 d7 34 a6 bc 17 b9 cd 73 70 e7 2a ae 31
00:36:51.493: amai: : 80 b7 c8 1e 50 b1 ce 72 9d e7 f6 bd cb 55 bd a8
00:36:51.545: amai: : 2f 7f 62 d4 7a 01 da 6a db f7 db ee 86 77 2b 6d
00:36:51.599: amai: : 1e 1e 67 ef 2c ac d7 63 56 f3 90 7d 96 86 2c 82
00:36:51.650: amai: : 2a 90 e0 ec 1f da 40 c3
00:36:51.702: amai: : -----------------------------------------------
00:36:51.753: ASR progress: Sending payload
00:36:51.813: amai: AMAuthInstallRembrandtMeasureElf: [hash section: 248 bytes]
00:36:51.945: amai: : 30 00 00 00 05 00 00 00 57 ad 80 ac 99 4f 9c 5a
00:36:52.035: amai: : 2b 62 11 14 f4 fe 61 a3 6f 52 0a 61 bf 48 75 ff
00:36:52.085: amai: : ea de 86 71 17 88 8e d1 31 8e 9f 8b 66 e7 37 be
00:36:52.139: amai: : 5f fa 44 46 b8 5f 1a 2a 44 88 de db cd 51 3b bd
00:36:52.190: amai: : 23 6c 05 01 48 42 34 74 2c a3 14 c5 c7 d4 1f d6
00:36:52.241: amai: : 06 c7 e2 a9 a1 96 e2 76 0f 9f d7 83 2b ed 88 b3
00:36:52.291: amai: : 65 6f b6 0f ad 8d b4 f3 9f 85 a8 c7 d4 ad 4c 6c
00:36:52.343: amai: : b7 95 f1 2b 25 df 6e 70 d0 b6 02 59 54 9a a7 27
00:36:52.475: amai: : 79 fd e2 6f 13 83 f4 f7 42 ba 57 47 6e ba a7 0f
00:36:52.525: amai: : f3 9c b9 2f 23 eb 17 6e 0c fe 11 2c 08 c9 bc e3
00:36:52.584: amai: : 48 32 0a 23 4e b8 77 51 04 3f 4e ab 8e 7d 39 cf
00:36:52.643: amai: : ae 7b 5c 2f 1e 08 f2 e4 49 b5 90 c4 78 43 01 1c
00:36:52.706: amai: : b5 e8 73 c0 78 59 ed 49 d3 41 e0 3e 26 0e 5a 36
00:36:52.756: amai: : 76 29 21 ab 35 9e 00 6b 8d 92 9b fc 55 85 31 96
00:36:52.806: amai: : 61 c5 7b 3d 31 a5 c8 2b c4 fb 9c 9c fd b1 8e 89
00:36:52.857: amai: : 1b 2b e5 35 b7 2e fd 47
00:36:52.907: amai: : -----------------------------------------------
00:36:52.957: amai: BbfwReaderFindAndCopyFileData: failed to find bbfw item "vinyl/update/main/signedprofile.der": File error
00:36:53.008: amai: BbfwReaderFindAndCopyFileData: failed to find bbfw item "vinyl/update/gold/signedprofile.der": File error
00:36:53.060: amai: AMAuthInstallIsICE19BBGoldCertIDECDSA: GoldCertId: 1F3F5BDF
00:36:53.110: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BasebandFirmware to Manifest to personalize later
00:36:53.161: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting OS to Manifest to personalize later
00:36:53.212: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RecoveryMode to Manifest to personalize later
00:36:53.264: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Liquid to Manifest to personalize later
00:36:53.317: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow0 to Manifest to personalize later
00:36:53.367: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AVE to Manifest to personalize later
00:36:53.417: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ANE to Manifest to personalize later
00:36:53.468: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Ap,HapticAssets to Manifest to personalize later
00:36:53.518: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryPlugin to Manifest to personalize later
00:36:53.569: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreSEP to Manifest to personalize later
00:36:53.620: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting ISP to Manifest to personalize later
00:36:53.671: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SEP to Manifest to personalize later
00:36:53.721: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting iBoot to Manifest to personalize later
00:36:53.772: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting RestoreTrustCache to Manifest to personalize later
00:36:53.823: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet1 to Manifest to personalize later
00:36:53.873: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting DeviceTree to Manifest to personalize later
00:36:53.925: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AudioCodecFirmware to Manifest to personalize later
00:36:53.995: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting PMP to Manifest to personalize later
00:36:54.051: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LeapHaptics to Manifest to personalize later
00:36:54.101: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting StaticTrustCache to Manifest to personalize later
00:36:54.152: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging0 to Manifest to personalize later
00:36:54.203: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LLB to Manifest to personalize later
00:36:54.253: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryLow1 to Manifest to personalize later
00:36:54.303: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryFull to Manifest to personalize later
00:36:54.354: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AppleLogo to Manifest to personalize later
00:36:54.406: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting SIO to Manifest to personalize later
00:36:54.456: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting BatteryCharging1 to Manifest to personalize later
00:36:54.507: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting GFX to Manifest to personalize later
00:36:54.558: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting AOP to Manifest to personalize later
00:36:54.611: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting LowPowerWallet0 to Manifest to personalize later
00:36:54.662: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting WCHFirmwareUpdater to Manifest to personalize later
00:36:54.713: amai: _AMAuthInstallBundleCopyOverrideBuildIdentity: Inserting Multitouch to Manifest to personalize later
00:36:54.763: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbProvisioningManifestKeyHash = <CFDa
                     ta 0x7f9603c229d0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x238c5118db979840969fb4dba3ab2db3 ... 162
                     9e2a30e1df392}
00:36:54.814: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbActivationManifestKeyHash = <CFData
                     0x7f9603c6dda0 [0x7fff88086cc0]>{length = 48, capacity = 48, bytes = 0x1b41607650ebf11c6b39f41cb267dc64 ... 055803
                     e1ef81c870}
00:36:54.925: amai: _AMAuthInstallBundleSetBasebandKeyHashes: setting (from build manifest): BbFDRSecurityKeyHash = <CFData 0x7f9
                     603c0e7c0 [0x7fff88086cc0]>{length = 0, capacity = 0, bytes = 0x}
00:36:55.052: amai: _AMAuthInstallBundleCreateServerRequestDictionary: ticketPath amai/apimg4ticket.der , withApTicket is False,  (!Tru
                     e && ( False || False))
00:36:55.104: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreLogo"
00:36:55.161: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreDeviceTree"
00:36:55.212: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreKernelCache"
00:36:55.264: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreRamDisk"
00:36:55.330: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "OSRamdisk" not part of manifest, skipping
00:36:55.381: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBEC"
00:36:55.461: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBSS"
00:36:55.511: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "KernelCache"
00:36:55.561: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftap" entry
00:36:55.612: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfta" entry
00:36:55.663: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "ftsp" entry
00:36:55.714: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "rfts" entry
00:36:55.765: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,SystemVolumeCanonicalMetadata"
00:36:55.819: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolumeCanonicalMetadata" not part of manife
                     st, skipping
00:36:55.870: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "BaseSystemVolume" not part of manifest, skipping
00:36:55.928: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,BaseSystemVolume" not part of manifest, skipping
00:36:55.979: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SystemVolume"
00:36:56.030: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "x86,SystemVolume" not part of manifest, skipping
00:36:56.081: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Ap,BaseSystemTrustCache" not part of manifest, skipping
00:36:56.132: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Diags" not part of manifest, skipping
00:36:56.185: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "CFELoader" not part of manifest, skipping
00:36:56.239: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "RBM" not part of manifest, skipping
00:36:56.290: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PHLEET" not part of manifest, skipping
00:36:56.347: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PERTOS" not part of manifest, skipping
00:36:56.398: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "PEHammer" not part of manifest, skipping
00:36:56.448: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "Alamo" not part of manifest, skipping
00:36:56.502: amai: _AMAuthInstallBundleCreateServerRequestDictionary: entry "BasebandFirmware" has been previously personalized; sk
                     ipping it
00:36:56.554: amai: _AMAuthInstallBundleCreateServerRequestDictionary: skipping "OS" entry
00:36:56.604: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RecoveryMode"
00:36:56.655: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Liquid"
00:36:56.705: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow0"
00:36:56.755: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AVE"
00:36:56.806: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ANE"
00:36:56.858: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Ap,HapticAssets"
00:36:56.912: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryPlugin"
00:36:56.963: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreSEP"
00:36:57.015: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "ISP"
00:36:57.068: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SEP"
00:36:57.120: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "iBoot"
00:36:57.171: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "RestoreTrustCache"
00:36:57.222: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet1"
00:36:57.272: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "DeviceTree"
00:36:57.323: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AudioCodecFirmware"
00:36:57.374: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "PMP"
00:36:57.425: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LeapHaptics"
00:36:57.475: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "StaticTrustCache"
00:36:57.525: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging0"
00:36:57.575: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LLB"
00:36:57.626: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryLow1"
00:36:57.677: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryFull"
00:36:57.728: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AppleLogo"
00:36:57.779: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "SIO"
00:36:57.829: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "BatteryCharging1"
00:36:57.880: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "GFX"
00:36:57.930: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "AOP"
00:36:57.981: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "LowPowerWallet0"
00:36:58.033: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "WCHFirmwareUpdater"
00:36:58.087: amai: _AMAuthInstallBundleCreateServerRequestDictionary: not personalizing "Multitouch"
00:36:58.137: amai: AMSupportPlatformCreateBufferFromNativeFilePath: open failed: No such file or directory
00:36:58.188: amai: AMSupportPlatformCreateBufferFromNativeFilePath: /usr/local/standalone/firmware/device_map.plist
00:36:58.239: amai: AMAuthInstallApCopyDeviceEntryFromDeviceMap: Failed to read devicemap from file:///usr/local/standalone/firmwa
                     re/device_map.plist
00:36:58.290: amai: AMAuthInstallApImg4ServerRequestAddUIDMode: Could not check if UID mode is required.
00:36:58.340: amai: _AddUpdaterTags: updater->requestTags is NULL
00:36:58.391: amai: _AddUpdaterTags: updater->requestTags is NULL
00:36:58.442: amai: _AMAuthInstallBundleCreateServerRequestDictionary: nothing to be done
00:36:58.493: Setting kAMRestoreOptionsiBootEANNuke.
00:36:58.543: <Restore Device 0x7f9603d65960>: operation 13 progress 6
00:36:58.544:  Sending file system via ASR 6%
00:36:58.595: sock  14: connected to  [usbmux_3]:49169
00:36:58.645: Completed checkpoint id: 0x1325 (await_update_usbc)
00:36:58.697: Started checkpoint id: 0x131D (update_ace3)
00:36:58.747: <Restore Device 0x7f9603d65960>: operation 85 progress 0
00:36:58.798: <Restore Device 0x7f9603d65960>: operation 85 progress 100
00:36:58.848: Completed checkpoint id: 0x131D (update_ace3)
00:36:58.899: Started checkpoint id: 0x1318 (update_usbcretimer)
00:36:58.951: <Restore Device 0x7f9603d65960>: operation 82 progress 0
00:36:59.005: <Restore Device 0x7f9603d65960>: operation 82 progress 100
00:36:59.056: Completed checkpoint id: 0x1318 (update_usbcretimer)
00:36:59.106: Started checkpoint id: 0x1331 (await_update_manta_mcu)
00:36:59.156: Completed checkpoint id: 0x1331 (await_update_manta_mcu)
00:36:59.207: Started checkpoint id: 0x1330 (await_update_stockholm)
00:36:59.258: Completed checkpoint id: 0x1330 (await_update_stockholm)
00:36:59.314: Started checkpoint id: 0x132A (await_update_baseband_legacy)
00:36:59.365: <Restore Device 0x7f9603d65960>: operation 13 progress 7
00:36:59.366:  Sending file system via ASR 7%
00:36:59.417: sock  14: closed
00:36:59.467: ASR progress: Sending payload
00:36:59.517: <Restore Device 0x7f9603d65960>: operation 13 progress 8
00:36:59.518:  Sending file system via ASR 8%
00:36:59.569: ASR progress: Sending payload
00:36:59.621: <Restore Device 0x7f9603d65960>: operation 13 progress 9
00:36:59.622:  Sending file system via ASR 9%
00:36:59.673: ASR progress: Sending payload
00:36:59.723: <Restore Device 0x7f9603d65960>: operation 13 progress 10
00:36:59.724:  Sending file system via ASR 10%
00:36:59.775: ASR progress: Sending payload
00:36:59.825: <Restore Device 0x7f9603d65960>: operation 13 progress 11
00:36:59.825:  Sending file system via ASR 11%
00:36:59.876: amai: AMAuthInstallBasebandHandleUpdaterStatus: commandAccepted: YES
00:36:59.927: amai: AMAuthInstallBasebandHandleUpdaterStatus: outputDict: {
00:36:59.978: 00:37:00.030:     CertID = 524245983;
00:37:00.082:     ChipID = 104;
00:37:00.132: 00:37:00.183:     FusingStatus = 3;
00:37:00.239:     ManifestInfo =     {
00:37:00.289:         CMStatusCode = 0;
00:37:00.340:         FCMStatusCode = 64;
00:37:00.391:         PMStatusCode = 0;
00:37:00.441: 00:37:00.492:         SKeyStatus = 0;
00:37:00.542:     };
00:37:00.593: 00:37:00.644:     VendorID = 2;
00:37:00.695:     attemptedToFuse = 0;
00:37:00.746:     done = 1;
00:37:00.797: }
00:37:00.848: Completed checkpoint id: 0x132A (await_update_baseband_legacy)
00:37:00.898: <Restore Device 0x7f9603d65960>: operation 65 progress 0
00:37:00.949: Started checkpoint id: 0x132E (await_update_rose)
00:37:01.001: requested restore behavior: Erase
00:37:01.005:  Flash mode: Don't Retain User's Data While Flashing
00:37:01.059: requested restore behavior: Erase
00:37:01.059:  Flash mode: Don't Retain User's Data While Flashing
00:37:01.109: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: is
                     Recovery = 0, entry = Rap,SoftwareBinaryDsp1
00:37:01.162: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3
                     _22D64_Restore/Firmware/Rose/r1p0/ftab.bin
00:37:01.212: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/Rose/r1p0/ftab.bin
00:37:01.264: amai: _handleFirmwareUpdaterRequest: Rose updater has device-generated RestoreInfo
00:37:01.315: requested restore behavior: Erase
00:37:01.316:  Flash mode: Don't Retain User's Data While Flashing
00:37:01.368: repersonalization is ON for Rose updater
00:37:01.430: amai: AMAuthInstallUpdaterPersonalize: Adding AP fusing information to coprocessor TSS request.
00:37:01.481: amai: AMAuthInstallUpdaterCreateResponse: Updater local signing support: false
00:37:01.532: amai: AMAuthInstallRequestSendSyncWithHeader: SSO function returned NULL and no SSO token was provided, SSO disabl
                     ed.
00:37:01.583: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-request.plist
00:37:01.634: amai: tss_submit_job_with_retry: TSS Connection attempt 1 of 3.  (Will retry if TSS_ERR_SERVER_NOT_REACHABLE.)
00:37:01.684: ASR progress: Sending payload
00:37:01.734: amai: -[AMSupportStaticURLSession URLSession:didReceiveChallenge:completionHandler:]: Authentication challenge receive
                     d.  Method: NSURLAuthenticationMethodServerTrust
00:37:01.785: amai: AMAuthInstallRequestSendSyncWithHeader: received tss response (server version: 2.1.0)
00:37:01.835: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-response.plist
00:37:01.886: amai: AMAuthInstallUpdaterPersonalize: Stashing Rose ticket(s) in bundle (LoopInstance=(null))
00:37:01.937: <Restore Device 0x7f9603d65960>: operation 13 progress 12
00:37:01.939:  Sending file system via ASR 12%
00:37:01.990: <Restore Device 0x7f9603d65960>: operation 65 progress 100
00:37:02.040: <Restore Device 0x7f9603d65960>: operation 59 progress 0
00:37:02.042:  Updating SE firmware
00:37:02.092: Completed checkpoint id: 0x132E (await_update_rose)
00:37:02.144: Started checkpoint id: 0x132F (await_update_se)
00:37:02.196: ASR progress: Sending payload
00:37:02.246: requested restore behavior: Erase
00:37:02.246:  Flash mode: Don't Retain User's Data While Flashing
00:37:02.298: requested restore behavior: Erase
00:37:02.298:  Flash mode: Don't Retain User's Data While Flashing
00:37:02.353: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: 
                     isRecovery = 0, entry = SE,UpdatePayload
00:37:02.403: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.
                     3_22D64_Restore/Firmware/SE/Stockholm6.RELEASE.sefw
00:37:02.454: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/SE/Stockholm6.RELEASE.sefw
00:37:02.506: <Restore Device 0x7f9603d65960>: operation 13 progress 13
00:37:02.506:  Sending file system via ASR 13%
00:37:02.556: amai: _handleFirmwareUpdaterRequest: SE updater has device-generated RestoreInfo
00:37:02.607: requested restore behavior: Erase
00:37:02.607:  Flash mode: Don't Retain User's Data While Flashing
00:37:02.657: repersonalization is ON for SE updater
00:37:02.708: amai: AMAuthInstallUpdaterPersonalize: Adding AP fusing information to coprocessor TSS request.
00:37:02.760: amai: AMAuthInstallUpdaterCreateResponse: Updater local signing support: false
00:37:02.811: amai: AMAuthInstallRequestSendSyncWithHeader: SSO function returned NULL and no SSO token was provided, SSO disable
                     d.
00:37:02.862: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-request.plist
00:37:02.912: amai: tss_submit_job_with_retry: TSS Connection attempt 1 of 3.  (Will retry if TSS_ERR_SERVER_NOT_REACHABLE.)
00:37:02.962: amai: -[AMSupportStaticURLSession URLSession:didReceiveChallenge:completionHandler:]: Authentication challenge receiv
                     ed.  Method: NSURLAuthenticationMethodServerTrust
00:37:03.013: amai: AMAuthInstallRequestSendSyncWithHeader: received tss response (server version: 2.1.0)
00:37:03.063: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-response.plist
00:37:03.114: amai: AMAuthInstallUpdaterPersonalize: Stashing SE ticket(s) in bundle (LoopInstance=(null))
00:37:03.164: ASR progress: Sending payload
00:37:03.216: <Restore Device 0x7f9603d65960>: operation 13 progress 14
00:37:03.216:  Sending file system via ASR 14%
00:37:03.268: ASR progress: Sending payload
00:37:03.319: <Restore Device 0x7f9603d65960>: operation 13 progress 15
00:37:03.319:  Sending file system via ASR 15%
00:37:03.370: ASR progress: Sending payload
00:37:03.420: <Restore Device 0x7f9603d65960>: operation 13 progress 16
00:37:03.420:  Sending file system via ASR 16%
00:37:03.471: <Restore Device 0x7f9603d65960>: operation 13 progress 17
00:37:03.472:  Sending file system via ASR 17%
00:37:03.526: ASR progress: Sending payload
00:37:03.580: <Restore Device 0x7f9603d65960>: operation 13 progress 18
00:37:03.580:  Sending file system via ASR 18%
00:37:03.632: ASR progress: Sending payload
00:37:03.682: <Restore Device 0x7f9603d65960>: operation 13 progress 19
00:37:03.683:  Sending file system via ASR 19%
00:37:03.733: ASR progress: Sending payload
00:37:03.783: <Restore Device 0x7f9603d65960>: operation 13 progress 20
00:37:03.783:  Sending file system via ASR 20%
00:37:03.834: ASR progress: Sending payload
00:37:03.884: <Restore Device 0x7f9603d65960>: operation 13 progress 21
00:37:03.885:  Sending file system via ASR 21%
00:37:03.935: ASR progress: Sending payload
00:37:03.987: <Restore Device 0x7f9603d65960>: operation 13 progress 22
00:37:03.987:  Sending file system via ASR 22%
00:37:04.038: ASR progress: Sending payload
00:37:04.094: <Restore Device 0x7f9603d65960>: operation 13 progress 23
00:37:04.095:  Sending file system via ASR 23%
00:37:04.145: ASR progress: Sending payload
00:37:04.196: <Restore Device 0x7f9603d65960>: operation 13 progress 24
00:37:04.196:  Sending file system via ASR 24%
00:37:04.246: ASR progress: Sending payload
00:37:04.297: <Restore Device 0x7f9603d65960>: operation 13 progress 25
00:37:04.298:  Sending file system via ASR 25%
00:37:04.348: ASR progress: Sending payload
00:37:04.399: <Restore Device 0x7f9603d65960>: operation 13 progress 26
00:37:04.399:  Sending file system via ASR 26%
00:37:04.450: ASR progress: Sending payload
00:37:04.501: <Restore Device 0x7f9603d65960>: operation 13 progress 27
00:37:04.501:  Sending file system via ASR 27%
00:37:04.552: ASR progress: Sending payload
00:37:04.602: <Restore Device 0x7f9603d65960>: operation 13 progress 28
00:37:04.603:  Sending file system via ASR 28%
00:37:04.653: ASR progress: Sending payload
00:37:04.704: <Restore Device 0x7f9603d65960>: operation 13 progress 29
00:37:04.704:  Sending file system via ASR 29%
00:37:04.755: Completed checkpoint id: 0x132F (await_update_se)
00:37:04.806: Started checkpoint id: 0x132D (await_update_vinyl)
00:37:04.859: Completed checkpoint id: 0x132D (await_update_vinyl)
00:37:04.910: Started checkpoint id: 0x132C (await_update_update_veridian)
00:37:04.961: Completed checkpoint id: 0x132C (await_update_update_veridian)
00:37:05.013: Started checkpoint id: 0x1324 (update_appletconnuarp)
00:37:05.064: Completed checkpoint id: 0x1324 (update_appletconnuarp)
00:37:05.114: Completed checkpoint id: 0x635 (update_device_firmware)
00:37:05.165: Started checkpoint id: 0x63C (verify_fdr_data)
00:37:05.215: Completed checkpoint id: 0x63C (verify_fdr_data)
00:37:05.265: Started checkpoint id: 0x668 (update_firmware_post_sealing)
00:37:05.316: Started checkpoint id: 0x1501 (update_savage_postseal)
00:37:05.367: <Restore Device 0x7f9603d65960>: operation 60 progress -1
00:37:05.367:  Updating biometrics sensor firmware
00:37:05.417: Completed checkpoint id: 0x1501 (update_savage_postseal)
00:37:05.467: Started checkpoint id: 0x1500 (decompress_pearl_data)
00:37:05.518: <Restore Device 0x7f9603d65960>: operation 60 progress -1
00:37:05.519:  Updating biometrics sensor firmware
00:37:05.570: ASR progress: Sending payload
00:37:05.620: <Restore Device 0x7f9603d65960>: operation 13 progress 30
00:37:05.620:  Sending file system via ASR 30%
00:37:05.670: ASR progress: Sending payload
00:37:05.721: <Restore Device 0x7f9603d65960>: operation 13 progress 31
00:37:05.722:  Sending file system via ASR 31%
00:37:05.772: ASR progress: Sending payload
00:37:05.822: <Restore Device 0x7f9603d65960>: operation 13 progress 32
00:37:05.822:  Sending file system via ASR 32%
00:37:05.873: ASR progress: Sending payload
00:37:05.923: <Restore Device 0x7f9603d65960>: operation 13 progress 33
00:37:05.927:  Sending file system via ASR 33%
00:37:05.977: <Restore Device 0x7f9603d65960>: operation 13 progress 34
00:37:05.977:  Sending file system via ASR 34%
00:37:06.028: ASR progress: Sending payload
00:37:06.078: <Restore Device 0x7f9603d65960>: operation 13 progress 35
00:37:06.120:  Sending file system via ASR 35%
00:37:06.181: ASR progress: Sending payload
00:37:06.734: load
00:37:07.785: <Restore Device 0x7f9603d65960>: operation 13 progress 36
00:37:07.785:  Sending file system via ASR 36%
00:37:08.335: ASR progress: Sending payload
00:37:09.886: <Restore Device 0x7f9603d65960>: operation 13 progress 37
00:37:09.886:  Sending file system via ASR 37%
00:37:09.938: ASR progress: Sending payload
00:37:11.990: Completed checkpoint id: 0x1500 (decompress_pearl_data)
00:37:12.042: Started checkpoint id: 0x1503 (update_rose_postseal)
00:37:12.092: <Restore Device 0x7f9603d65960>: operation 65 progress 0
00:37:12.144: requested restore behavior: Erase
00:37:12.144:  Flash mode: Don't Retain User's Data While Flashing
00:37:12.194: requested restore behavior: Erase
00:37:12.197:  Flash mode: Don't Retain User's Data While Flashing
00:37:12.248: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: i
                     sRecovery = 0, entry = Rap,SoftwareBinaryDsp1
00:37:12.300: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3
                     _22D64_Restore/Firmware/Rose/r1p0/ftab.bin
00:37:12.852: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/Rose/r1p0/ftab.bin
00:37:12.903: <Restore Device 0x7f9603d65960>: operation 13 progress 38
00:37:12.903:  Sending file system via ASR 38%
00:37:12.954: amai: _handleFirmwareUpdaterRequest: Rose updater has device-generated RestoreInfo
00:37:13.005: requested restore behavior: Erase
00:37:13.005:  Flash mode: Don't Retain User's Data While Flashing
00:37:13.056: repersonalization is ON for Rose updater
00:37:13.107: amai: AMAuthInstallUpdaterPersonalize: Adding AP fusing information to coprocessor TSS request.
00:37:13.157: amai: AMAuthInstallUpdaterCreateResponse: Updater local signing support: false
00:37:13.208: amai: AMAuthInstallRequestSendSyncWithHeader: SSO function returned NULL and no SSO token was provided, SSO disabl
                     ed.
00:37:13.259: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-request.plist
00:37:13.321: amai: tss_submit_job_with_retry: TSS Connection attempt 1 of 3.  (Will retry if TSS_ERR_SERVER_NOT_REACHABLE.)
00:37:13.372: amai: -[AMSupportStaticURLSession URLSession:didReceiveChallenge:completionHandler:]: Authentication challenge receive
                     d.  Method: NSURLAuthenticationMethodServerTrust
00:37:13.923: ASR progress: Sending payload
00:37:13.975: amai: AMAuthInstallRequestSendSyncWithHeader: received tss response (server version: 2.1.0)
00:37:14.026: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-response.plist
00:37:14.077: amai: AMAuthInstallUpdaterPersonalize: Stashing Rose ticket(s) in bundle (LoopInstance=(null))
00:37:15.128: <Restore Device 0x7f9603d65960>: operation 65 progress 100
00:37:15.179: Completed checkpoint id: 0x1503 (update_rose_postseal)
00:37:15.229: Started checkpoint id: 0x131A (stage_fdr_ean)
00:37:15.285: Completed checkpoint id: 0x131A (stage_fdr_ean)
00:37:15.339: Started checkpoint id: 0x1319 (ensure_fdr_ean)
00:37:15.389: Completed checkpoint id: 0x1319 (ensure_fdr_ean)
00:37:15.440: Started checkpoint id: 0x1504 (update_fdr_ean)
00:37:15.490: <Restore Device 0x7f9603d65960>: operation 74 progress -1
00:37:15.624: <Restore Device 0x7f9603d65960>: operation 74 progress 100
00:37:15.688: Completed checkpoint id: 0x1504 (update_fdr_ean)
00:37:15.739: Started checkpoint id: 0x1314 (update_fillmore)
00:37:15.790: Completed checkpoint id: 0x1314 (update_fillmore)
00:37:15.840: Completed checkpoint id: 0x668 (update_firmware_post_sealing)
00:37:15.936: Started checkpoint id: 0x63D (fdr_verify_sealed_manifest)
00:37:15.996: Completed checkpoint id: 0x63D (fdr_verify_sealed_manifest)
00:37:16.047: Started checkpoint id: 0x66F (commit_sep_os)
00:37:16.097: <Restore Device 0x7f9603d65960>: operation 13 progress 39
00:37:16.097:  Sending file system via ASR 39%
00:37:16.648: ASR progress: Sending payload
00:37:18.203: <Restore Device 0x7f9603d65960>: operation 13 progress 40
00:37:18.205:  Sending file system via ASR 40%
00:37:19.256: ASR progress: Sending payload
00:37:20.307: <Restore Device 0x7f9603d65960>: operation 13 progress 41
00:37:20.307:  Sending file system via ASR 41%
00:37:20.857: ASR progress: Sending payload
00:37:21.909: <Restore Device 0x7f9603d65960>: operation 13 progress 42
00:37:21.909:  Sending file system via ASR 42%
00:37:23.461: ASR progress: Sending payload
00:37:25.013: <Restore Device 0x7f9603d65960>: operation 13 progress 43
00:37:25.014:  Sending file system via ASR 43%
00:37:26.067: ASR progress: Sending payload
00:37:27.118: <Restore Device 0x7f9603d65960>: operation 13 progress 44
00:37:27.118:  Sending file system via ASR 44%
00:37:28.170: ASR progress: Sending payload
00:37:29.221: <Restore Device 0x7f9603d65960>: operation 13 progress 45
00:37:29.221:  Sending file system via ASR 45%
00:37:29.272: Completed checkpoint id: 0x66F (commit_sep_os)
00:37:29.322: Started checkpoint id: 0x6B4 (await_system_image_invert_retry)
00:37:29.373: <Restore Device 0x7f9603d65960>: operation 13 progress 45
00:37:29.373:  Sending file system via ASR 45%
00:37:30.425: ASR progress: Sending payload
00:37:30.976: <Restore Device 0x7f9603d65960>: operation 13 progress 46
00:37:30.977:  Sending file system via ASR 46%
00:37:32.529: ASR progress: Sending payload
00:37:33.080: <Restore Device 0x7f9603d65960>: operation 13 progress 47
00:37:33.081:  Sending file system via ASR 47%
00:37:34.637: ASR progress: Sending payload
00:37:35.188: <Restore Device 0x7f9603d65960>: operation 13 progress 48
00:37:35.189:  Sending file system via ASR 48%
00:37:36.741: ASR progress: Sending payload
00:37:36.791: <Restore Device 0x7f9603d65960>: operation 13 progress 49
00:37:36.791:  Sending file system via ASR 49%
00:37:38.846: ASR progress: Sending payload
00:37:38.898: <Restore Device 0x7f9603d65960>: operation 13 progress 50
00:37:38.898:  Sending file system via ASR 50%
00:37:40.961: <Restore Device 0x7f9603d65960>: operation 13 progress 51
00:37:40.961:  Sending file system via ASR 51%
00:37:41.012: ASR progress: Sending payload
00:37:43.567: <Restore Device 0x7f9603d65960>: operation 13 progress 52
00:37:43.567:  Sending file system via ASR 52%
00:37:43.618: ASR progress: Sending payload
00:37:45.670: <Restore Device 0x7f9603d65960>: operation 13 progress 53
00:37:45.671:  Sending file system via ASR 53%
00:37:45.722: ASR progress: Sending payload
00:37:47.272: <Restore Device 0x7f9603d65960>: operation 13 progress 54
00:37:47.273:  Sending file system via ASR 54%
00:37:47.825: ASR progress: Sending payload
00:37:49.376: <Restore Device 0x7f9603d65960>: operation 13 progress 55
00:37:49.376:  Sending file system via ASR 55%
00:37:49.927: ASR progress: Sending payload
00:37:50.984: <Restore Device 0x7f9603d65960>: operation 13 progress 56
00:37:50.988:  Sending file system via ASR 56%
00:37:52.039: ASR progress: Sending payload
00:37:53.091: <Restore Device 0x7f9603d65960>: operation 13 progress 57
00:37:53.092:  Sending file system via ASR 57%
00:37:54.143: ASR progress: Sending payload
00:37:55.195: <Restore Device 0x7f9603d65960>: operation 13 progress 58
00:37:55.195:  Sending file system via ASR 58%
00:37:56.249: ASR progress: Sending payload
00:37:57.313: <Restore Device 0x7f9603d65960>: operation 13 progress 59
00:37:57.314:  Sending file system via ASR 59%
00:37:58.865: ASR progress: Sending payload
00:37:59.916: <Restore Device 0x7f9603d65960>: operation 13 progress 60
00:37:59.917:  Sending file system via ASR 60%
00:38:00.971: ASR progress: Sending payload
00:38:02.023: <Restore Device 0x7f9603d65960>: operation 13 progress 61
00:38:02.023:  Sending file system via ASR 61%
00:38:03.576: ASR progress: Sending payload
00:38:04.127: <Restore Device 0x7f9603d65960>: operation 13 progress 62
00:38:04.127:  Sending file system via ASR 62%
00:38:05.678: ASR progress: Sending payload
00:38:06.230: <Restore Device 0x7f9603d65960>: operation 13 progress 63
00:38:06.230:  Sending file system via ASR 63%
00:38:07.782: ASR progress: Sending payload
00:38:08.332: <Restore Device 0x7f9603d65960>: operation 13 progress 64
00:38:08.333:  Sending file system via ASR 64%
00:38:09.885: ASR progress: Sending payload
00:38:09.935: <Restore Device 0x7f9603d65960>: operation 13 progress 65
00:38:09.936:  Sending file system via ASR 65%
00:38:12.488: ASR progress: Sending payload
00:38:12.539: <Restore Device 0x7f9603d65960>: operation 13 progress 66
00:38:12.540:  Sending file system via ASR 66%
00:38:14.592: <Restore Device 0x7f9603d65960>: operation 13 progress 67
00:38:14.592:  Sending file system via ASR 67%
00:38:14.643: ASR progress: Sending payload
00:38:16.194: <Restore Device 0x7f9603d65960>: operation 13 progress 68
00:38:16.194:  Sending file system via ASR 68%
00:38:16.745: ASR progress: Sending payload
00:38:18.296: <Restore Device 0x7f9603d65960>: operation 13 progress 69
00:38:18.296:  Sending file system via ASR 69%
00:38:18.847: ASR progress: Sending payload
00:38:20.398: <Restore Device 0x7f9603d65960>: operation 13 progress 70
00:38:20.399:  Sending file system via ASR 70%
00:38:20.949: ASR progress: Sending payload
00:38:22.003: <Restore Device 0x7f9603d65960>: operation 13 progress 71
00:38:22.003:  Sending file system via ASR 71%
00:38:22.554: ASR progress: Sending payload
00:38:24.106: <Restore Device 0x7f9603d65960>: operation 13 progress 72
00:38:24.106:  Sending file system via ASR 72%
00:38:24.657: ASR progress: Sending payload
00:38:25.708: <Restore Device 0x7f9603d65960>: operation 13 progress 73
00:38:25.708:  Sending file system via ASR 73%
00:38:26.760: ASR progress: Sending payload
00:38:27.811: <Restore Device 0x7f9603d65960>: operation 13 progress 74
00:38:27.811:  Sending file system via ASR 74%
00:38:28.863: ASR progress: Sending payload
00:38:29.914: <Restore Device 0x7f9603d65960>: operation 13 progress 75
00:38:29.915:  Sending file system via ASR 75%
00:38:30.966: ASR progress: Sending payload
00:38:32.018: <Restore Device 0x7f9603d65960>: operation 13 progress 76
00:38:32.018:  Sending file system via ASR 76%
00:38:33.070: ASR progress: Sending payload
00:38:34.121: <Restore Device 0x7f9603d65960>: operation 13 progress 77
00:38:34.122:  Sending file system via ASR 77%
00:38:35.173: ASR progress: Sending payload
00:38:35.724: <Restore Device 0x7f9603d65960>: operation 13 progress 78
00:38:35.724:  Sending file system via ASR 78%
00:38:37.275: ASR progress: Sending payload
00:38:37.827: <Restore Device 0x7f9603d65960>: operation 13 progress 79
00:38:37.827:  Sending file system via ASR 79%
00:38:38.878: ASR progress: Sending payload
00:38:39.429: <Restore Device 0x7f9603d65960>: operation 13 progress 80
00:38:39.430:  Sending file system via ASR 80%
00:38:41.481: ASR progress: Sending payload
00:38:42.535: <Restore Device 0x7f9603d65960>: operation 13 progress 81
00:38:42.535:  Sending file system via ASR 81%
00:38:44.088: ASR progress: Sending payload
00:38:44.140: <Restore Device 0x7f9603d65960>: operation 13 progress 82
00:38:44.141:  Sending file system via ASR 82%
00:38:46.192: ASR progress: Sending payload
00:38:46.244: <Restore Device 0x7f9603d65960>: operation 13 progress 83
00:38:46.244:  Sending file system via ASR 83%
00:38:48.296: <Restore Device 0x7f9603d65960>: operation 13 progress 84
00:38:48.296:  Sending file system via ASR 84%
00:38:48.346: ASR progress: Sending payload
00:38:50.398: <Restore Device 0x7f9603d65960>: operation 13 progress 85
00:38:50.398:  Sending file system via ASR 85%
00:38:50.448: ASR progress: Sending payload
00:38:52.000: <Restore Device 0x7f9603d65960>: operation 13 progress 86
00:38:52.001:  Sending file system via ASR 86%
00:38:52.552: ASR progress: Sending payload
00:38:54.104: <Restore Device 0x7f9603d65960>: operation 13 progress 87
00:38:54.104:  Sending file system via ASR 87%
00:38:54.655: ASR progress: Sending payload
00:38:55.706: <Restore Device 0x7f9603d65960>: operation 13 progress 88
00:38:55.706:  Sending file system via ASR 88%
00:38:56.257: ASR progress: Sending payload
00:38:57.810: <Restore Device 0x7f9603d65960>: operation 13 progress 89
00:38:57.811:  Sending file system via ASR 89%
00:38:58.361: ASR progress: Sending payload
00:38:59.914: <Restore Device 0x7f9603d65960>: operation 13 progress 90
00:38:59.915:  Sending file system via ASR 90%
00:39:00.465: ASR progress: Sending payload
00:39:01.518: <Restore Device 0x7f9603d65960>: operation 13 progress 91
00:39:01.519:  Sending file system via ASR 91%
00:39:02.571: ASR progress: Sending payload
00:39:03.622: <Restore Device 0x7f9603d65960>: operation 13 progress 92
00:39:03.622:  Sending file system via ASR 92%
00:39:04.673: ASR progress: Sending payload
00:39:05.725: <Restore Device 0x7f9603d65960>: operation 13 progress 93
00:39:05.727:  Sending file system via ASR 93%
00:39:06.779: ASR progress: Sending payload
00:39:07.330: <Restore Device 0x7f9603d65960>: operation 13 progress 94
00:39:07.330:  Sending file system via ASR 94%
00:39:08.382: ASR progress: Sending payload
00:39:08.932: <Restore Device 0x7f9603d65960>: operation 13 progress 95
00:39:08.933:  Sending file system via ASR 95%
00:39:10.486: ASR progress: Sending payload
00:39:11.037: <Restore Device 0x7f9603d65960>: operation 13 progress 96
00:39:11.037:  Sending file system via ASR 96%
00:39:13.090: ASR progress: Sending payload
00:39:13.642: <Restore Device 0x7f9603d65960>: operation 13 progress 97
00:39:13.642:  Sending file system via ASR 97%
00:39:15.195: ASR progress: Sending payload
00:39:15.248: <Restore Device 0x7f9603d65960>: operation 13 progress 98
00:39:15.248:  Sending file system via ASR 98%
00:39:17.301: ASR progress: Sending payload
00:39:17.352: <Restore Device 0x7f9603d65960>: operation 13 progress 99
00:39:17.352:  Sending file system via ASR 99%
00:39:18.905: <Restore Device 0x7f9603d65960>: operation 13 progress 100
00:39:18.905:  Sending file system via ASR 100%
00:39:18.956: <Restore Device 0x7f9603d65960>: operation 14 progress 0
00:39:18.956:  Verifying file system via ASR 0%
00:39:19.508: <Restore Device 0x7f9603d65960>: operation 14 progress 1
00:39:19.508:  Verifying file system via ASR 1%
00:39:19.559: <Restore Device 0x7f9603d65960>: operation 14 progress 2
00:39:19.559:  Verifying file system via ASR 2%
00:39:19.610: <Restore Device 0x7f9603d65960>: operation 14 progress 3
00:39:19.611:  Verifying file system via ASR 3%
00:39:19.661: <Restore Device 0x7f9603d65960>: operation 14 progress 4
00:39:19.661:  Verifying file system via ASR 4%
00:39:20.213: <Restore Device 0x7f9603d65960>: operation 14 progress 5
00:39:20.214:  Verifying file system via ASR 5%
00:39:20.265: <Restore Device 0x7f9603d65960>: operation 14 progress 6
00:39:20.265:  Verifying file system via ASR 6%
00:39:20.316: <Restore Device 0x7f9603d65960>: operation 14 progress 7
00:39:20.316:  Verifying file system via ASR 7%
00:39:20.366: <Restore Device 0x7f9603d65960>: operation 14 progress 8
00:39:20.368:  Verifying file system via ASR 8%
00:39:20.919: <Restore Device 0x7f9603d65960>: operation 14 progress 9
00:39:20.919:  Verifying file system via ASR 9%
00:39:20.971: <Restore Device 0x7f9603d65960>: operation 14 progress 10
00:39:20.972:  Verifying file system via ASR 10%
00:39:21.022: <Restore Device 0x7f9603d65960>: operation 14 progress 11
00:39:21.022:  Verifying file system via ASR 11%
00:39:21.073: <Restore Device 0x7f9603d65960>: operation 14 progress 12
00:39:21.073:  Verifying file system via ASR 12%
00:39:21.124: <Restore Device 0x7f9603d65960>: operation 14 progress 13
00:39:21.124:  Verifying file system via ASR 13%
00:39:21.676: <Restore Device 0x7f9603d65960>: operation 14 progress 14
00:39:21.676:  Verifying file system via ASR 14%
00:39:21.727: <Restore Device 0x7f9603d65960>: operation 14 progress 15
00:39:21.727:  Verifying file system via ASR 15%
00:39:21.779: <Restore Device 0x7f9603d65960>: operation 14 progress 16
00:39:21.779:  Verifying file system via ASR 16%
00:39:21.829: <Restore Device 0x7f9603d65960>: operation 14 progress 17
00:39:21.829:  Verifying file system via ASR 17%
00:39:22.381: <Restore Device 0x7f9603d65960>: operation 14 progress 18
00:39:22.397:  Verifying file system via ASR 18%
00:39:22.448: <Restore Device 0x7f9603d65960>: operation 14 progress 19
00:39:22.448:  Verifying file system via ASR 19%
00:39:22.499: <Restore Device 0x7f9603d65960>: operation 14 progress 20
00:39:22.499:  Verifying file system via ASR 20%
00:39:22.550: <Restore Device 0x7f9603d65960>: operation 14 progress 21
00:39:22.550:  Verifying file system via ASR 21%
00:39:23.102: <Restore Device 0x7f9603d65960>: operation 14 progress 22
00:39:23.103:  Verifying file system via ASR 22%
00:39:23.154: <Restore Device 0x7f9603d65960>: operation 14 progress 23
00:39:23.155:  Verifying file system via ASR 23%
00:39:23.206: <Restore Device 0x7f9603d65960>: operation 14 progress 24
00:39:23.206:  Verifying file system via ASR 24%
00:39:23.257: <Restore Device 0x7f9603d65960>: operation 14 progress 25
00:39:23.257:  Verifying file system via ASR 25%
00:39:23.308: <Restore Device 0x7f9603d65960>: operation 14 progress 26
00:39:23.308:  Verifying file system via ASR 26%
00:39:23.860: <Restore Device 0x7f9603d65960>: operation 14 progress 27
00:39:23.861:  Verifying file system via ASR 27%
00:39:23.911: <Restore Device 0x7f9603d65960>: operation 14 progress 28
00:39:23.912:  Verifying file system via ASR 28%
00:39:23.963: <Restore Device 0x7f9603d65960>: operation 14 progress 29
00:39:23.963:  Verifying file system via ASR 29%
00:39:24.013: <Restore Device 0x7f9603d65960>: operation 14 progress 30
00:39:24.014:  Verifying file system via ASR 30%
00:39:24.566: <Restore Device 0x7f9603d65960>: operation 14 progress 31
00:39:24.566:  Verifying file system via ASR 31%
00:39:24.616: <Restore Device 0x7f9603d65960>: operation 14 progress 32
00:39:24.617:  Verifying file system via ASR 32%
00:39:24.668: <Restore Device 0x7f9603d65960>: operation 14 progress 33
00:39:24.668:  Verifying file system via ASR 33%
00:39:24.718: <Restore Device 0x7f9603d65960>: operation 14 progress 34
00:39:24.719:  Verifying file system via ASR 34%
00:39:25.269: <Restore Device 0x7f9603d65960>: operation 14 progress 35
00:39:25.269:  Verifying file system via ASR 35%
00:39:25.320: <Restore Device 0x7f9603d65960>: operation 14 progress 36
00:39:25.320:  Verifying file system via ASR 36%
00:39:25.371: <Restore Device 0x7f9603d65960>: operation 14 progress 37
00:39:25.372:  Verifying file system via ASR 37%
00:39:25.423: <Restore Device 0x7f9603d65960>: operation 14 progress 38
00:39:25.423:  Verifying file system via ASR 38%
00:39:25.475: <Restore Device 0x7f9603d65960>: operation 14 progress 39
00:39:25.476:  Verifying file system via ASR 39%
00:39:26.028: <Restore Device 0x7f9603d65960>: operation 14 progress 40
00:39:26.028:  Verifying file system via ASR 40%
00:39:26.078: <Restore Device 0x7f9603d65960>: operation 14 progress 41
00:39:26.078:  Verifying file system via ASR 41%
00:39:26.129: <Restore Device 0x7f9603d65960>: operation 14 progress 42
00:39:26.129:  Verifying file system via ASR 42%
00:39:26.180: <Restore Device 0x7f9603d65960>: operation 14 progress 43
00:39:26.181:  Verifying file system via ASR 43%
00:39:26.732: <Restore Device 0x7f9603d65960>: operation 14 progress 44
00:39:26.732:  Verifying file system via ASR 44%
00:39:26.782: <Restore Device 0x7f9603d65960>: operation 14 progress 45
00:39:26.783:  Verifying file system via ASR 45%
00:39:26.834: <Restore Device 0x7f9603d65960>: operation 14 progress 46
00:39:26.834:  Verifying file system via ASR 46%
00:39:26.885: <Restore Device 0x7f9603d65960>: operation 14 progress 47
00:39:26.885:  Verifying file system via ASR 47%
00:39:27.435: <Restore Device 0x7f9603d65960>: operation 14 progress 48
00:39:27.435:  Verifying file system via ASR 48%
00:39:27.486: <Restore Device 0x7f9603d65960>: operation 14 progress 49
00:39:27.486:  Verifying file system via ASR 49%
00:39:27.538: <Restore Device 0x7f9603d65960>: operation 14 progress 50
00:39:27.538:  Verifying file system via ASR 50%
00:39:27.589: <Restore Device 0x7f9603d65960>: operation 14 progress 51
00:39:27.590:  Verifying file system via ASR 51%
00:39:28.143: <Restore Device 0x7f9603d65960>: operation 14 progress 52
00:39:28.144:  Verifying file system via ASR 52%
00:39:28.195: <Restore Device 0x7f9603d65960>: operation 14 progress 53
00:39:28.195:  Verifying file system via ASR 53%
00:39:28.245: <Restore Device 0x7f9603d65960>: operation 14 progress 54
00:39:28.246:  Verifying file system via ASR 54%
00:39:28.296: <Restore Device 0x7f9603d65960>: operation 14 progress 55
00:39:28.296:  Verifying file system via ASR 55%
00:39:28.347: <Restore Device 0x7f9603d65960>: operation 14 progress 56
00:39:28.347:  Verifying file system via ASR 56%
00:39:28.899: <Restore Device 0x7f9603d65960>: operation 14 progress 57
00:39:28.900:  Verifying file system via ASR 57%
00:39:28.950: <Restore Device 0x7f9603d65960>: operation 14 progress 58
00:39:28.950:  Verifying file system via ASR 58%
00:39:29.003: <Restore Device 0x7f9603d65960>: operation 14 progress 59
00:39:29.003:  Verifying file system via ASR 59%
00:39:29.054: <Restore Device 0x7f9603d65960>: operation 14 progress 60
00:39:29.054:  Verifying file system via ASR 60%
00:39:29.606: <Restore Device 0x7f9603d65960>: operation 14 progress 61
00:39:29.606:  Verifying file system via ASR 61%
00:39:29.657: <Restore Device 0x7f9603d65960>: operation 14 progress 62
00:39:29.659:  Verifying file system via ASR 62%
00:39:29.710: <Restore Device 0x7f9603d65960>: operation 14 progress 63
00:39:29.711:  Verifying file system via ASR 63%
00:39:29.762: <Restore Device 0x7f9603d65960>: operation 14 progress 64
00:39:29.762:  Verifying file system via ASR 64%
00:39:30.314: <Restore Device 0x7f9603d65960>: operation 14 progress 65
00:39:30.314:  Verifying file system via ASR 65%
00:39:30.365: <Restore Device 0x7f9603d65960>: operation 14 progress 66
00:39:30.365:  Verifying file system via ASR 66%
00:39:30.416: <Restore Device 0x7f9603d65960>: operation 14 progress 67
00:39:30.416:  Verifying file system via ASR 67%
00:39:30.467: <Restore Device 0x7f9603d65960>: operation 14 progress 68
00:39:30.467:  Verifying file system via ASR 68%
00:39:30.518: <Restore Device 0x7f9603d65960>: operation 14 progress 69
00:39:30.518:  Verifying file system via ASR 69%
00:39:31.069: <Restore Device 0x7f9603d65960>: operation 14 progress 70
00:39:31.069:  Verifying file system via ASR 70%
00:39:31.120: <Restore Device 0x7f9603d65960>: operation 14 progress 71
00:39:31.121:  Verifying file system via ASR 71%
00:39:31.171: <Restore Device 0x7f9603d65960>: operation 14 progress 72
00:39:31.172:  Verifying file system via ASR 72%
00:39:31.222: <Restore Device 0x7f9603d65960>: operation 14 progress 73
00:39:31.223:  Verifying file system via ASR 73%
00:39:31.775: <Restore Device 0x7f9603d65960>: operation 14 progress 74
00:39:31.776:  Verifying file system via ASR 74%
00:39:31.828: <Restore Device 0x7f9603d65960>: operation 14 progress 75
00:39:31.828:  Verifying file system via ASR 75%
00:39:31.879: <Restore Device 0x7f9603d65960>: operation 14 progress 76
00:39:31.879:  Verifying file system via ASR 76%
00:39:31.930: <Restore Device 0x7f9603d65960>: operation 14 progress 77
00:39:31.930:  Verifying file system via ASR 77%
00:39:32.480: <Restore Device 0x7f9603d65960>: operation 14 progress 78
00:39:32.480:  Verifying file system via ASR 78%
00:39:32.530: <Restore Device 0x7f9603d65960>: operation 14 progress 79
00:39:32.531:  Verifying file system via ASR 79%
00:39:32.581: <Restore Device 0x7f9603d65960>: operation 14 progress 80
00:39:32.582:  Verifying file system via ASR 80%
00:39:32.632: <Restore Device 0x7f9603d65960>: operation 14 progress 81
00:39:32.633:  Verifying file system via ASR 81%
00:39:33.184: <Restore Device 0x7f9603d65960>: operation 14 progress 82
00:39:33.185:  Verifying file system via ASR 82%
00:39:33.236: <Restore Device 0x7f9603d65960>: operation 14 progress 83
00:39:33.238:  Verifying file system via ASR 83%
00:39:33.289: <Restore Device 0x7f9603d65960>: operation 14 progress 84
00:39:33.289:  Verifying file system via ASR 84%
00:39:33.340: <Restore Device 0x7f9603d65960>: operation 14 progress 85
00:39:33.340:  Verifying file system via ASR 85%
00:39:33.390: <Restore Device 0x7f9603d65960>: operation 14 progress 86
00:39:33.391:  Verifying file system via ASR 86%
00:39:33.942: <Restore Device 0x7f9603d65960>: operation 14 progress 87
00:39:33.942:  Verifying file system via ASR 87%
00:39:33.993: <Restore Device 0x7f9603d65960>: operation 14 progress 88
00:39:33.995:  Verifying file system via ASR 88%
00:39:34.046: <Restore Device 0x7f9603d65960>: operation 14 progress 89
00:39:34.048:  Verifying file system via ASR 89%
00:39:34.099: <Restore Device 0x7f9603d65960>: operation 14 progress 90
00:39:34.099:  Verifying file system via ASR 90%
00:39:34.650: <Restore Device 0x7f9603d65960>: operation 14 progress 91
00:39:34.651:  Verifying file system via ASR 91%
00:39:34.701: <Restore Device 0x7f9603d65960>: operation 14 progress 92
00:39:34.702:  Verifying file system via ASR 92%
00:39:34.753: <Restore Device 0x7f9603d65960>: operation 14 progress 93
00:39:34.753:  Verifying file system via ASR 93%
00:39:34.804: <Restore Device 0x7f9603d65960>: operation 14 progress 94
00:39:34.804:  Verifying file system via ASR 94%
00:39:35.356: <Restore Device 0x7f9603d65960>: operation 14 progress 95
00:39:35.356:  Verifying file system via ASR 95%
00:39:35.407: <Restore Device 0x7f9603d65960>: operation 14 progress 96
00:39:35.407:  Verifying file system via ASR 96%
00:39:35.457: <Restore Device 0x7f9603d65960>: operation 14 progress 97
00:39:35.458:  Verifying file system via ASR 97%
00:39:35.508: <Restore Device 0x7f9603d65960>: operation 14 progress 98
00:39:35.508:  Verifying file system via ASR 98%
00:39:36.061: <Restore Device 0x7f9603d65960>: operation 14 progress 99
00:39:36.061:  Verifying file system via ASR 99%
00:39:36.113: ASR progress: Finished
00:39:36.165: sock  12: shutdown(SHUT_WR) failed: Socket is not connected
00:39:36.216: sock  12: closed
00:39:36.267: <Restore Device 0x7f9603d65960>: operation 14 progress 100
00:39:36.267:  Verifying file system via ASR 100%
00:39:36.317: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:39:36.318:  Closing the mounting of the drive
00:39:36.369: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:39:36.369:  Closing the mounting of the drive
00:39:36.419: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:39:36.419:  Closing the mounting of the drive
00:39:36.469: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:39:36.470:  Closing the mounting of the drive
00:39:36.520: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:39:36.520:  Closing the mounting of the drive
00:39:36.570: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:39:36.571:  Closing the mounting of the drive
00:39:41.130: <Restore Device 0x7f9603d65960>: operation 16 progress -1
00:39:41.130:  Mounting file system
00:39:41.181: <Restore Device 0x7f9603d65960>: operation 16 progress -1
00:39:41.181:  Mounting file system
00:39:41.732: <Restore Device 0x7f9603d65960>: operation 16 progress -1
00:39:41.733:  Mounting file system
00:39:41.783: <Restore Device 0x7f9603d65960>: operation 16 progress -1
00:39:41.785:  Mounting file system
00:39:41.836: Completed checkpoint id: 0x6B4 (await_system_image_invert_retry)
00:39:41.888: Started checkpoint id: 0x674 (create_protected_filesystems)
00:39:41.940: <Restore Device 0x7f9603d65960>: operation 67 progress -1
00:40:03.026: Completed checkpoint id: 0x674 (create_protected_filesystems)
00:40:03.077: Started checkpoint id: 0x65F (reserve_overprov_space)
00:40:03.129: Completed checkpoint id: 0x65F (reserve_overprov_space)
00:40:03.180: Started checkpoint id: 0x680 (read_new_os_build_version)
00:40:03.232: Completed checkpoint id: 0x680 (read_new_os_build_version)
00:40:03.282: Started checkpoint id: 0x6A6 (install_splat)
00:40:03.332: requested restore behavior: Erase
00:40:03.332:  Flash mode: Don't Retain User's Data While Flashing
00:40:03.383: amai: _handleFirmwareUpdaterRequest: Cryptex1 updater has device-generated RestoreInfo
00:40:03.434: requested restore behavior: Erase
00:40:03.436:  Flash mode: Don't Retain User's Data While Flashing
00:40:03.487: repersonalization is ON for Cryptex1 updater
00:40:03.538: amai: AMAuthInstallUpdaterPersonalize: Adding AP fusing information to coprocessor TSS request.
00:40:03.589: amai: AMAuthInstallUpdaterCreateResponse: Updater local signing support: false
00:40:03.639: amai: AMAuthInstallRequestSendSyncWithHeader: SSO function returned NULL and no SSO token was provided, SSO disab
                     led.
00:40:03.691: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-request.plist
00:40:03.742: amai: tss_submit_job_with_retry: TSS Connection attempt 1 of 3.  (Will retry if TSS_ERR_SERVER_NOT_REACHABLE.)
00:40:03.794: amai: -[AMSupportStaticURLSession URLSession:didReceiveChallenge:completionHandler:]: Authentication challenge receiv
                     ed.  Method: NSURLAuthenticationMethodServerTrust
00:40:03.845: amai: AMAuthInstallRequestSendSyncWithHeader: received tss response (server version: 2.1.0)
00:40:03.895: amai: AMAuthInstallDebugWriteObject: debug object written: file:///tmp/PersonalizedBundle_636BAECC-8063-45C0-8368
                     -4CE5F33FD2E4/amai/debug/tss-response.plist
00:40:03.961: amai: AMAuthInstallUpdaterPersonalize: Stashing Cryptex1 ticket(s) in bundle (LoopInstance=(null))
00:40:04.019: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: i
                     sRecovery = 0, entry = Cryptex1,SystemOS
00:40:04.083: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.
                     3_22D64_Restore/044-94201-001.dmg.aea
00:40:04.634: <Restore Device 0x7f9603d65960>: operation 78 progress 1
00:40:04.690: <Restore Device 0x7f9603d65960>: operation 78 progress 2
00:40:05.245: <Restore Device 0x7f9603d65960>: operation 78 progress 3
00:40:05.805: <Restore Device 0x7f9603d65960>: operation 78 progress 4
00:40:06.368: <Restore Device 0x7f9603d65960>: operation 78 progress 5
00:40:06.419: <Restore Device 0x7f9603d65960>: operation 78 progress 6
00:40:06.969: <Restore Device 0x7f9603d65960>: operation 78 progress 7
00:40:07.525: <Restore Device 0x7f9603d65960>: operation 78 progress 8
00:40:08.077: <Restore Device 0x7f9603d65960>: operation 78 progress 9
00:40:08.628: <Restore Device 0x7f9603d65960>: operation 78 progress 10
00:40:09.179: <Restore Device 0x7f9603d65960>: operation 78 progress 11
00:40:09.229: <Restore Device 0x7f9603d65960>: operation 78 progress 12
00:40:09.780: <Restore Device 0x7f9603d65960>: operation 78 progress 13
00:40:10.330: <Restore Device 0x7f9603d65960>: operation 78 progress 14
00:40:10.887: <Restore Device 0x7f9603d65960>: operation 78 progress 15
00:40:10.939: <Restore Device 0x7f9603d65960>: operation 78 progress 16
00:40:12.115: <Restore Device 0x7f9603d65960>: operation 78 progress 17
00:40:12.169: <Restore Device 0x7f9603d65960>: operation 78 progress 18
00:40:12.727: <Restore Device 0x7f9603d65960>: operation 78 progress 19
00:40:13.284: <Restore Device 0x7f9603d65960>: operation 78 progress 20
00:40:13.835: <Restore Device 0x7f9603d65960>: operation 78 progress 21
00:40:13.886: <Restore Device 0x7f9603d65960>: operation 78 progress 22
00:40:14.437: <Restore Device 0x7f9603d65960>: operation 78 progress 23
00:40:14.988: <Restore Device 0x7f9603d65960>: operation 78 progress 24
00:40:15.539: <Restore Device 0x7f9603d65960>: operation 78 progress 25
00:40:15.589: <Restore Device 0x7f9603d65960>: operation 78 progress 26
00:40:16.140: <Restore Device 0x7f9603d65960>: operation 78 progress 27
00:40:16.691: <Restore Device 0x7f9603d65960>: operation 78 progress 28
00:40:17.251: <Restore Device 0x7f9603d65960>: operation 78 progress 29
00:40:17.303: <Restore Device 0x7f9603d65960>: operation 78 progress 30
00:40:17.854: <Restore Device 0x7f9603d65960>: operation 78 progress 31
00:40:18.411: <Restore Device 0x7f9603d65960>: operation 78 progress 32
00:40:18.962: <Restore Device 0x7f9603d65960>: operation 78 progress 33
00:40:19.012: <Restore Device 0x7f9603d65960>: operation 78 progress 34
00:40:19.565: <Restore Device 0x7f9603d65960>: operation 78 progress 35
00:40:20.120: <Restore Device 0x7f9603d65960>: operation 78 progress 36
00:40:20.672: <Restore Device 0x7f9603d65960>: operation 78 progress 37
00:40:20.723: <Restore Device 0x7f9603d65960>: operation 78 progress 38
00:40:21.275: <Restore Device 0x7f9603d65960>: operation 78 progress 39
00:40:21.828: <Restore Device 0x7f9603d65960>: operation 78 progress 40
00:40:22.380: <Restore Device 0x7f9603d65960>: operation 78 progress 41
00:40:22.482: <Restore Device 0x7f9603d65960>: operation 78 progress 42
00:40:23.077: <Restore Device 0x7f9603d65960>: operation 78 progress 43
00:40:23.642: <Restore Device 0x7f9603d65960>: operation 78 progress 44
00:40:24.193: <Restore Device 0x7f9603d65960>: operation 78 progress 45
00:40:24.744: <Restore Device 0x7f9603d65960>: operation 78 progress 46
00:40:24.819: <Restore Device 0x7f9603d65960>: operation 78 progress 47
00:40:25.380: <Restore Device 0x7f9603d65960>: operation 78 progress 48
00:40:25.932: <Restore Device 0x7f9603d65960>: operation 78 progress 49
00:40:26.483: <Restore Device 0x7f9603d65960>: operation 78 progress 50
00:40:26.534: <Restore Device 0x7f9603d65960>: operation 78 progress 51
00:40:27.085: <Restore Device 0x7f9603d65960>: operation 78 progress 52
00:40:27.636: <Restore Device 0x7f9603d65960>: operation 78 progress 53
00:40:28.191: <Restore Device 0x7f9603d65960>: operation 78 progress 54
00:40:28.242: <Restore Device 0x7f9603d65960>: operation 78 progress 55
00:40:28.793: <Restore Device 0x7f9603d65960>: operation 78 progress 56
00:40:29.345: <Restore Device 0x7f9603d65960>: operation 78 progress 57
00:40:29.902: <Restore Device 0x7f9603d65960>: operation 78 progress 58
00:40:30.453: <Restore Device 0x7f9603d65960>: operation 78 progress 59
00:40:30.505: <Restore Device 0x7f9603d65960>: operation 78 progress 60
00:40:31.060: <Restore Device 0x7f9603d65960>: operation 78 progress 61
00:40:31.613: <Restore Device 0x7f9603d65960>: operation 78 progress 62
00:40:32.170: <Restore Device 0x7f9603d65960>: operation 78 progress 63
00:40:32.221: <Restore Device 0x7f9603d65960>: operation 78 progress 64
00:40:32.782: <Restore Device 0x7f9603d65960>: operation 78 progress 65
00:40:33.333: <Restore Device 0x7f9603d65960>: operation 78 progress 66
00:40:33.886: <Restore Device 0x7f9603d65960>: operation 78 progress 67
00:40:34.442: <Restore Device 0x7f9603d65960>: operation 78 progress 68
00:40:34.499: <Restore Device 0x7f9603d65960>: operation 78 progress 69
00:40:35.055: <Restore Device 0x7f9603d65960>: operation 78 progress 70
00:40:35.605: <Restore Device 0x7f9603d65960>: operation 78 progress 71
00:40:35.656: <Restore Device 0x7f9603d65960>: operation 78 progress 72
00:40:36.215: <Restore Device 0x7f9603d65960>: operation 78 progress 73
00:40:36.766: <Restore Device 0x7f9603d65960>: operation 78 progress 74
00:40:37.317: <Restore Device 0x7f9603d65960>: operation 78 progress 75
00:40:37.367: <Restore Device 0x7f9603d65960>: operation 78 progress 76
00:40:37.919: <Restore Device 0x7f9603d65960>: operation 78 progress 77
00:40:38.470: <Restore Device 0x7f9603d65960>: operation 78 progress 78
00:40:39.021: <Restore Device 0x7f9603d65960>: operation 78 progress 79
00:40:39.573: <Restore Device 0x7f9603d65960>: operation 78 progress 80
00:40:40.124: <Restore Device 0x7f9603d65960>: operation 78 progress 81
00:40:40.175: <Restore Device 0x7f9603d65960>: operation 78 progress 82
00:40:40.730: <Restore Device 0x7f9603d65960>: operation 78 progress 83
00:40:41.281: <Restore Device 0x7f9603d65960>: operation 78 progress 84
00:40:42.334: <Restore Device 0x7f9603d65960>: operation 78 progress 85
00:40:42.910: <Restore Device 0x7f9603d65960>: operation 78 progress 86
00:40:43.972: <Restore Device 0x7f9603d65960>: operation 78 progress 87
00:40:44.526: <Restore Device 0x7f9603d65960>: operation 78 progress 88
00:40:45.077: <Restore Device 0x7f9603d65960>: operation 78 progress 89
00:40:45.628: <Restore Device 0x7f9603d65960>: operation 78 progress 90
00:40:45.679: <Restore Device 0x7f9603d65960>: operation 78 progress 91
00:40:46.244: <Restore Device 0x7f9603d65960>: operation 78 progress 92
00:40:46.795: <Restore Device 0x7f9603d65960>: operation 78 progress 93
00:40:47.347: <Restore Device 0x7f9603d65960>: operation 78 progress 94
00:40:47.898: <Restore Device 0x7f9603d65960>: operation 78 progress 95
00:40:47.963: <Restore Device 0x7f9603d65960>: operation 78 progress 96
00:40:48.514: <Restore Device 0x7f9603d65960>: operation 78 progress 97
00:40:49.065: <Restore Device 0x7f9603d65960>: operation 78 progress 98
00:40:49.616: <Restore Device 0x7f9603d65960>: operation 78 progress 99
00:40:49.666: <Restore Device 0x7f9603d65960>: operation 78 progress 100
00:40:49.717: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/044-94201-001.dmg.aea
00:40:49.780: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: 
                     isRecovery = 0, entry = Cryptex1,SystemVolume
00:40:49.832: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.
                     3_22D64_Restore/Firmware/044-94201-001.dmg.aea.root_hash
00:40:49.882: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/044-94201-001.dmg.aea.root_hash
00:40:49.934: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: 
                     isRecovery = 0, entry = Cryptex1,SystemTrustCache
00:40:49.984: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.
                     3_22D64_Restore/Firmware/044-94201-001.dmg.aea.trustcache
00:40:50.034: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/044-94201-001.dmg.aea.trustcache
00:40:50.085: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: 
                     isRecovery = 0, entry = Cryptex1,AppOS
00:40:50.138: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3
                     _22D64_Restore/044-94825-001.dmg
00:40:50.234: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/044-94825-001.dmg
00:40:50.285: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: 
                     isRecovery = 0, entry = Cryptex1,AppVolume
00:40:50.335: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.
                     3_22D64_Restore/Firmware/044-94825-001.dmg.root_hash
00:40:50.386: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/044-94825-001.dmg.root_hash
00:40:50.437: amai: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: AMAuthInstallBundleCreateURLForKeyEntryInBuildIdentity: 
                     isRecovery = 0, entry = Cryptex1,AppTrustCache
00:40:50.487: sending source boot object from path: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.
                     3_22D64_Restore/Firmware/044-94825-001.dmg.trustcache
00:40:50.538: Sent image successfully from: /Users/masud/Downloads/3uToolsDownloads/Firmcache/iPhone12,3,iPhone12,5_18.3_22D64
                     _Restore/Firmware/044-94825-001.dmg.trustcache
00:40:50.588: Completed checkpoint id: 0x6A6 (install_splat)
00:40:50.638: Started checkpoint id: 0x628 (install_kernel_cache)
00:40:50.689: Started checkpoint id: 0xE00 (install_kernel_cache)
00:40:50.740: requested restore behavior: Erase
00:40:50.740:  Flash mode: Don't Retain User's Data While Flashing
00:40:50.795: <Restore Device 0x7f9603d65960>: operation 27 progress -1
00:40:50.846: <Restore Device 0x7f9603d65960>: operation 27 progress -1
00:40:50.897: Completed checkpoint id: 0xE00 (install_kernel_cache)
00:40:50.948: Started checkpoint id: 0xE01 (install_device_tree)
00:40:51.000: requested restore behavior: Erase
00:40:51.000:  Flash mode: Don't Retain User's Data While Flashing
00:40:51.053: <Restore Device 0x7f9603d65960>: operation 61 progress -1
00:40:51.053:  Downloading sub-firmware via network
00:40:51.103: <Restore Device 0x7f9603d65960>: operation 61 progress -1
00:40:51.103:  Downloading sub-firmware via network
00:40:51.154: Completed checkpoint id: 0xE01 (install_device_tree)
00:40:51.205: Started checkpoint id: 0xE05 (install_root_hash)
00:40:51.256: requested restore behavior: Erase
00:40:51.259:  Flash mode: Don't Retain User's Data While Flashing
00:40:51.310: <Restore Device 0x7f9603d65960>: operation 77 progress -1
00:40:51.361: Completed checkpoint id: 0xE05 (install_root_hash)
00:40:51.413: Started checkpoint id: 0xE03 (write_ticket)
00:40:51.464: Completed checkpoint id: 0xE03 (write_ticket)
00:40:51.515: Completed checkpoint id: 0x628 (install_kernel_cache)
00:40:51.566: Started checkpoint id: 0x64D (check_mounted)
00:40:51.617: Started checkpoint id: 0xF00 (fixup_var)
00:40:51.669: <Restore Device 0x7f9603d65960>: operation 17 progress -1
00:40:51.754: <Restore Device 0x7f9603d65960>: operation 50 progress -1
00:40:51.772:  Configuring keychain
00:40:56.833: Completed checkpoint id: 0xF00 (fixup_var)
00:40:56.883: Started checkpoint id: 0xF01 (restore_ota_logs)
00:40:56.934: Completed checkpoint id: 0xF01 (restore_ota_logs)
00:40:56.985: Started checkpoint id: 0xF04 (create_partition_mountpoints)
00:40:57.037: Completed checkpoint id: 0xF04 (create_partition_mountpoints)
00:40:57.088: Started checkpoint id: 0xF10 (create_production_dcrt)
00:40:57.139: sock  12: connected to  [fe80::98f5:bfff:feff:2a0%en3]:49161 as [fe80::14aa:5f22:bd0d:28ad%en3]:51542
00:40:57.189: [PurpleReverseProxy]: Feb 05 00:40:56 iTunesFlash[4281] <Error>: RPSocket.cpp:228(signal): No client callback, missing eve
                     nt 8 for socket 0x7f9603c82170
00:40:59.744: sock  12: connected to  [fe80::98f5:bfff:feff:2a0%en3]:49161 as [fe80::14aa:5f22:bd0d:28ad%en3]:51543
00:41:01.799: [PurpleReverseProxy]: Feb 05 00:41:01 iTunesFlash[4281] <Error>: RPSocket.cpp:228(signal): No client callback, missing even
                     t 8 for socket 0x7f9603c82170
00:41:01.852: Completed checkpoint id: 0xF10 (create_production_dcrt)
00:41:01.903: Completed checkpoint id: 0x64D (check_mounted)
00:41:01.954: Started checkpoint id: 0x6BF (attest_restore)
00:41:02.005: Returning cached value false for attestation enabled
00:41:02.056: Completed checkpoint id: 0x6BF (attest_restore)
00:41:02.107: Started checkpoint id: 0x69E (set_one_time_boot_command)
00:41:02.157: Completed checkpoint id: 0x69E (set_one_time_boot_command)
00:41:02.209: Started checkpoint id: 0x63B (set_nvram_variables)
00:41:02.260: Completed checkpoint id: 0x63B (set_nvram_variables)
00:41:02.316: Started checkpoint id: 0x639 (persistent_boot_args)
00:41:02.414: <Restore Device 0x7f9603d65960>: operation 25 progress -1
00:41:02.414:  Configuring startup parameter
00:41:02.464: Completed checkpoint id: 0x639 (persistent_boot_args)
00:41:02.515: Started checkpoint id: 0x65E (set_tdm)
00:41:02.565: Completed checkpoint id: 0x65E (set_tdm)
00:41:02.616: Started checkpoint id: 0x688 (populate_preboot_volume)
00:41:02.671: Completed checkpoint id: 0x688 (populate_preboot_volume)
00:41:02.774: Completed checkpoint id: 0x67B (perform_restore_installing)
00:41:02.824: Started checkpoint id: 0x1600 (recovery_os_restore)
00:41:02.875: Completed checkpoint id: 0x1600 (recovery_os_restore)
00:41:02.926: Started checkpoint id: 0x63F (set_boot_command)
00:41:02.992: Completed checkpoint id: 0x63F (set_boot_command)
00:41:03.043: Started checkpoint id: 0x68B (seal_system_volume)
00:41:03.104: requested restore behavior: Erase
00:41:03.104:  Flash mode: Don't Retain User's Data While Flashing
00:41:03.155: <Restore Device 0x7f9603d65960>: operation 77 progress -1
00:41:03.706: 1
00:41:25.795: requested restore behavior: Erase
00:41:25.795:  Flash mode: Don't Retain User's Data While Flashing
00:41:25.846: <Restore Device 0x7f9603d65960>: operation 77 progress -1
00:41:25.896: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:25.897:  Closing the mounting of the drive
00:41:25.948: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:25.948:  Closing the mounting of the drive
00:41:25.999: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:25.999:  Closing the mounting of the drive
00:41:26.050: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:26.050:  Closing the mounting of the drive
00:41:26.101: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:26.101:  Closing the mounting of the drive
00:41:26.152: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:26.152:  Closing the mounting of the drive
00:41:26.203: <Restore Device 0x7f9603d65960>: operation 77 progress -1
00:41:34.268: Completed checkpoint id: 0x68B (seal_system_volume)
00:41:34.319: Started checkpoint id: 0x669 (create_system_snapshot)
00:41:34.371: Completed checkpoint id: 0x669 (create_system_snapshot)
00:41:34.422: Started checkpoint id: 0x6B2 (prepare_data_split)
00:41:34.473: Completed checkpoint id: 0x6B2 (prepare_data_split)
00:41:34.524: Started checkpoint id: 0x6B1 (convert_eds_volumes)
00:41:34.575: Completed checkpoint id: 0x6B1 (convert_eds_volumes)
00:41:34.630: Started checkpoint id: 0x6AA (split_data_volume)
00:41:34.681: Completed checkpoint id: 0x6AA (split_data_volume)
00:41:34.732: Started checkpoint id: 0x6AB (commit_temporary_checkpoint)
00:41:34.783: Completed checkpoint id: 0x6AB (commit_temporary_checkpoint)
00:41:34.834: Started checkpoint id: 0x6BB (migrate_user_fsevents)
00:41:35.386: Completed checkpoint id: 0x6BB (migrate_user_fsevents)
00:41:35.437: Started checkpoint id: 0x640 (set_autoboot_delay)
00:41:35.489: Completed checkpoint id: 0x640 (set_autoboot_delay)
00:41:35.540: Started checkpoint id: 0x642 (unmount_filesystems)
00:41:35.590: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:35.592:  Closing the mounting of the drive
00:41:35.644: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:35.644:  Closing the mounting of the drive
00:41:35.696: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:35.697:  Closing the mounting of the drive
00:41:35.748: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:35.748:  Closing the mounting of the drive
00:41:35.799: <Restore Device 0x7f9603d65960>: operation 29 progress -1
00:41:35.799:  Closing the mounting of the drive
00:41:35.850: Completed checkpoint id: 0x642 (unmount_filesystems)
00:41:35.901: Started checkpoint id: 0x67C (cleanup_boot_command)
00:41:35.952: Completed checkpoint id: 0x67C (cleanup_boot_command)
00:41:36.003: Started checkpoint id: 0x1613 (cleanup_recovery_os_volume)
00:41:36.055: Completed checkpoint id: 0x1613 (cleanup_recovery_os_volume)
00:41:36.105: Started checkpoint id: 0x647 (cleanup_check_result)
00:41:36.156: Completed checkpoint id: 0x647 (cleanup_check_result)
00:41:36.208: Started checkpoint id: 0x6C2 (cleanup_send_crash_logs)
00:41:36.259: Completed checkpoint id: 0x6C2 (cleanup_send_crash_logs)
00:41:36.309: Started checkpoint id: 0x648 (cleanup_send_final_status)
00:41:36.361: device returned success
00:41:36.413: Sending acknowledgement that final status was received
00:41:36.463: <Restore Device 0x7f9603d65960>: Restore succeeded
00:41:36.515: Finished RestoreOS Restore Phase: Successful
00:41:36.515:  The flash is done
00:41:36.700:  Spent: -23 hour(s)-3 minutes

```
