കതിർ സ്വയം സഹായ സംഘം — PWA പാക്കേജ്

ഈ ZIP-ൽ:
- index.html: നിങ്ങളുടെ നിലവിലെ ആപ്പ്
- manifest.webmanifest: ഹോം സ്ക്രീൻ ഇൻസ്റ്റാൾ വിവരങ്ങൾ
- sw.js: അടിസ്ഥാന offline caching
- icons/: ആപ്പ് ഐക്കണുകൾ

ഇൻസ്റ്റാൾ ചെയ്യാൻ:
1. ഈ ZIP ഒരു HTTPS static hosting സേവനത്തിൽ upload ചെയ്യുക (ഉദാ. GitHub Pages).
2. ലഭിക്കുന്ന HTTPS വിലാസം Android Chrome-ൽ തുറക്കുക.
3. Chrome മെനുവിൽ Install app / Add to Home screen തിരഞ്ഞെടുക്കുക.

ഡാറ്റയെക്കുറിച്ച്:
- നിലവിലെ ആപ്പ് localStorage ഉപയോഗിക്കുന്നു; cloud sync അല്ല.
- പഴയ file:// പതിപ്പിലെ ഡാറ്റ പുതിയ HTTPS വിലാസത്തിലേക്ക് സ്വയം മാറില്ല.
- പഴയ ആപ്പിൽ Backup വിഭാഗം തുറന്ന് JSON backup ഡൗൺലോഡ് ചെയ്യുക.
- പുതിയ hosted ആപ്പിൽ Backup വിഭാഗത്തിൽ JSON ഫയൽ തിരഞ്ഞെടുത്ത് Restore ചെയ്യുക.
- Restore ചെയ്യുമ്പോൾ പുതിയ ആപ്പിലെ നിലവിലെ ഡാറ്റ മാറ്റിസ്ഥാപിക്കപ്പെടും.

ശ്രദ്ധിക്കുക:
ഈ പാക്കേജ് PWA ആയി ഇൻസ്റ്റാൾ ചെയ്യാൻ തയ്യാറാക്കിയതാണ്; ഇത് APK അല്ല.
ഒരു HTTPS hosting വിലാസം ആവശ്യമാണ്. സെക്രട്ടറി/ട്രഷറർ login, multi-device cloud sync എന്നിവ ഇതിൽ ഇതുവരെ ഇല്ല.
