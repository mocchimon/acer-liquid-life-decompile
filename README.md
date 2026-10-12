# acer-liquid-life-decompile
acer-liquid-life-decompile

Fully decompiled: Acer server authentication removed but left google aws in tact
Resigned with ApktoolM

Original APK
   │
   ├── Acer authentication
   │       ↓
   │   server token
   │       ↓
   └── dashboard

Patch
   │
   └── force existing skipLogin()
           ↓
       dashboard
           ↓
       BLE Liquid Leap
