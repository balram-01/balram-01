<!-- ═══════════════════════════════════════════════════════════
     BALIRAM SHEJAL — GITHUB PROFILE README
     All visuals: self-contained SVG or battle-tested services only
     (shields.io · github-readme-stats · streak-stats · capsule-render)
     ═══════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ── HERO HEADER SVG (100% self-contained, no external load) ── -->
<svg viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <!-- Deep space gradient -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#0f0c29"/>
      <stop offset="50%"  stop-color="#302b63"/>
      <stop offset="100%" stop-color="#24243e"/>
    </linearGradient>
    <!-- Purple glow radial -->
    <radialGradient id="glow1" cx="25%" cy="40%" r="45%">
      <stop offset="0%"   stop-color="#7c3aed" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#7c3aed" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glow2" cx="80%" cy="70%" r="40%">
      <stop offset="0%"   stop-color="#06b6d4" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#06b6d4" stop-opacity="0"/>
    </radialGradient>
    <!-- Shimmer animation for name -->
    <linearGradient id="shimmer" x1="-200%" y1="0%" x2="200%" y2="0%" gradientUnits="userSpaceOnUse">
      <stop offset="0%"   stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="40%"  stop-color="#e0d7ff" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#ffffff" stop-opacity="1"/>
      <stop offset="60%"  stop-color="#e0d7ff" stop-opacity="1"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
      <animateTransform attributeName="gradientTransform" type="translate" from="-900 0" to="900 0" dur="3s" repeatCount="indefinite"/>
    </linearGradient>
    <mask id="nameMask">
      <rect width="900" height="280" fill="white"/>
    </mask>
    <!-- Grid lines filter -->
    <filter id="softBlur">
      <feGaussianBlur stdDeviation="0.5"/>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="280" fill="url(#bg)" rx="16"/>
  <rect width="900" height="280" fill="url(#glow1)" rx="16"/>
  <rect width="900" height="280" fill="url(#glow2)" rx="16"/>

  <!-- Animated grid lines -->
  <g stroke="#7c3aed" stroke-width="0.4" opacity="0.18" filter="url(#softBlur)">
    <line x1="0" y1="40"  x2="900" y2="40"/>
    <line x1="0" y1="80"  x2="900" y2="80"/>
    <line x1="0" y1="120" x2="900" y2="120"/>
    <line x1="0" y1="160" x2="900" y2="160"/>
    <line x1="0" y1="200" x2="900" y2="200"/>
    <line x1="0" y1="240" x2="900" y2="240"/>
    <line x1="90"  y1="0" x2="90"  y2="280"/>
    <line x1="180" y1="0" x2="180" y2="280"/>
    <line x1="270" y1="0" x2="270" y2="280"/>
    <line x1="360" y1="0" x2="360" y2="280"/>
    <line x1="450" y1="0" x2="450" y2="280"/>
    <line x1="540" y1="0" x2="540" y2="280"/>
    <line x1="630" y1="0" x2="630" y2="280"/>
    <line x1="720" y1="0" x2="720" y2="280"/>
    <line x1="810" y1="0" x2="810" y2="280"/>
  </g>

  <!-- Orbiting dots -->
  <circle cx="760" cy="60" r="3" fill="#7c3aed" opacity="0.8">
    <animate attributeName="cy" values="60;50;60" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0.3;0.8" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="820" cy="100" r="2" fill="#06b6d4" opacity="0.6">
    <animate attributeName="cy" values="100;88;100" dur="3.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="3.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="80"  cy="200" r="2.5" fill="#a78bfa" opacity="0.7">
    <animate attributeName="cy" values="200;188;200" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="140" cy="50" r="1.8" fill="#06b6d4" opacity="0.5">
    <animate attributeName="cx" values="140;155;140" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- 3D floating card behind text -->
  <rect x="60" y="55" width="560" height="170" rx="14"
        fill="#1e1b4b" fill-opacity="0.55" stroke="#7c3aed" stroke-width="1" stroke-opacity="0.6"/>
  <!-- Card top edge highlight (3D effect) -->
  <rect x="60" y="55" width="560" height="3" rx="2" fill="#a78bfa" fill-opacity="0.5"/>

  <!-- NAME — shimmer text -->
  <text x="340" y="130" text-anchor="middle"
        font-family="'Segoe UI', system-ui, sans-serif" font-size="52" font-weight="900"
        letter-spacing="2" fill="url(#shimmer)">BALIRAM SHEJAL</text>
  <!-- NAME white base so shimmer overlays nicely -->
  <text x="340" y="130" text-anchor="middle"
        font-family="'Segoe UI', system-ui, sans-serif" font-size="52" font-weight="900"
        letter-spacing="2" fill="#ffffff" opacity="0.92">BALIRAM SHEJAL</text>

  <!-- Subtitle line 1 -->
  <text x="340" y="168" text-anchor="middle"
        font-family="'Segoe UI', system-ui, sans-serif" font-size="16" font-weight="600"
        fill="#a78bfa" letter-spacing="1">Senior Mobile Developer</text>

  <!-- Divider accent -->
  <line x1="210" y1="180" x2="470" y2="180" stroke="#7c3aed" stroke-width="1.5" stroke-opacity="0.7"/>
  <circle cx="340" cy="180" r="3" fill="#7c3aed"/>

  <!-- Subtitle line 2 -->
  <text x="340" y="200" text-anchor="middle"
        font-family="'Segoe UI', system-ui, sans-serif" font-size="13.5"
        fill="#94a3b8" letter-spacing="0.5">React Native  ·  Pure Kotlin Android  ·  Pune / Nagpur 🇮🇳</text>

  <!-- Stats row -->
  <g font-family="'Segoe UI', system-ui, sans-serif" font-size="12" fill="#cbd5e1">
    <text x="160" y="228" text-anchor="middle">📱 3+ Yrs Exp</text>
    <text x="285" y="228" text-anchor="middle">⭐ 1,840+ Installs</text>
    <text x="410" y="228" text-anchor="middle">🌍 160+ Countries</text>
    <text x="530" y="228" text-anchor="middle">📦 3 npm Packages</text>
  </g>

  <!-- Right-side floating 3D phone shape -->
  <g transform="translate(680, 55)">
    <!-- Phone body -->
    <rect x="0" y="10" width="80" height="155" rx="12"
          fill="#1e1b4b" stroke="#7c3aed" stroke-width="1.5"/>
    <!-- Phone screen -->
    <rect x="6" y="22" width="68" height="115" rx="6" fill="#0f172a"/>
    <!-- Screen glow -->
    <rect x="6" y="22" width="68" height="115" rx="6" fill="url(#glow1)" opacity="0.6"/>
    <!-- Code lines on screen -->
    <rect x="12" y="32" width="40" height="3" rx="2" fill="#7c3aed" opacity="0.9">
      <animate attributeName="width" values="40;50;40" dur="2s" repeatCount="indefinite"/>
    </rect>
    <rect x="12" y="40" width="55" height="3" rx="2" fill="#06b6d4" opacity="0.7"/>
    <rect x="12" y="48" width="30" height="3" rx="2" fill="#a78bfa" opacity="0.8">
      <animate attributeName="width" values="30;45;30" dur="3s" repeatCount="indefinite"/>
    </rect>
    <rect x="12" y="56" width="48" height="3" rx="2" fill="#06b6d4" opacity="0.6"/>
    <rect x="12" y="64" width="35" height="3" rx="2" fill="#7c3aed" opacity="0.9"/>
    <rect x="12" y="72" width="52" height="3" rx="2" fill="#94a3b8" opacity="0.5"/>
    <rect x="12" y="80" width="28" height="3" rx="2" fill="#a78bfa" opacity="0.7">
      <animate attributeName="width" values="28;42;28" dur="2.5s" repeatCount="indefinite"/>
    </rect>
    <rect x="12" y="88" width="45" height="3" rx="2" fill="#06b6d4" opacity="0.6"/>
    <rect x="12" y="96" width="38" height="3" rx="2" fill="#7c3aed" opacity="0.8"/>
    <rect x="12" y="104" width="56" height="3" rx="2" fill="#94a3b8" opacity="0.5"/>
    <rect x="12" y="112" width="32" height="3" rx="2" fill="#a78bfa" opacity="0.7"/>
    <rect x="12" y="120" width="44" height="3" rx="2" fill="#06b6d4" opacity="0.6"/>
    <!-- Home button -->
    <circle cx="40" cy="148" r="5" fill="none" stroke="#7c3aed" stroke-width="1.2"/>
    <!-- 3D shadow -->
    <rect x="5" y="165" width="80" height="6" rx="6" fill="#7c3aed" opacity="0.15"/>
    <!-- Floating animation on the whole phone -->
    <animateTransform attributeName="transform" additive="sum" type="translate"
      values="0,0; 0,-8; 0,0" dur="3s" repeatCount="indefinite"/>
  </g>

  <!-- Bottom wave -->
  <path d="M0 255 Q225 235 450 255 Q675 275 900 255 L900 280 L0 280 Z"
        fill="#0f0c29" fill-opacity="0.5"/>
</svg>

<br/>

<!-- ── SOCIAL BADGES (shields.io — most reliable) ── -->
<p>
  <img src="https://komarev.com/ghpvc/?username=balram-01&label=Profile+Views&color=7c3aed&style=for-the-badge" alt="views"/>
  &nbsp;
  <a href="https://www.linkedin.com/in/balram01/">
    <img src="https://img.shields.io/badge/LinkedIn-%20Baliram%20Shejal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:baliramshejal2001@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-baliramshejal2001-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/balram-01">
    <img src="https://img.shields.io/badge/GitHub-balram--01-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--  ABOUT ME  -->
<!-- ══════════════════════════════════════════════════════════ -->

## 👨‍💻 &nbsp;About Me

```kotlin
object BaliramShejal {

    val role       = "Senior Mobile Developer"
    val location   = "Pune / Nagpur, Maharashtra 🇮🇳"
    val experience = "3+ Years"
    val focus      = listOf("React Native 0.78", "Pure Kotlin Android", "Jetpack Compose")

    val currentProject = """
        ConnectApp — Complete Native Android Rewrite (React Native → Pure Kotlin)
        ↳ Telephony APIs · TOTP 2FA (RFC 6238) · NFC · Dual-SIM · VCF Scanner
    """

    val openSourcePackages = listOf(
        "@balram_01/react-native-dialpad   → Production-ready dialpad component",
        "react-native-shimmer-skeleton     → Reanimated 2 shimmer loader",
        "react-native-messager             → Native Android SMS bridge for RN"
    )

    val playStoreApps = mapOf(
        "AquaAlert"        to "⭐ 4.38 · 1,840+ installs · 160 countries · 20 languages",
        "SmartStepCounter" to "⭐ Ad-Free · GPS map · Jetpack Compose · Hardware sensor",
        "StatusDownloader" to "⭐ Privacy-first · Zero data collection · Offline only"
    )

    fun superpower() = "I rewrote an entire production calling app from RN → Pure Kotlin 🔁"
    fun learning()   = "Compose Multiplatform · Advanced Coroutines · KMP"
}
```

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--  TECH ARSENAL (3D card SVG — self-contained)  -->
<!-- ══════════════════════════════════════════════════════════ -->

## 🛠️ &nbsp;Tech Arsenal

<div align="center">

<!-- 3D TECH GRID SVG -->
<svg viewBox="0 0 860 400" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <linearGradient id="cardBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1e1b4b"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="purpleAccent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7c3aed"/>
      <stop offset="100%" stop-color="#06b6d4"/>
    </linearGradient>
    <filter id="cardShadow" x="-5%" y="-5%" width="115%" height="130%">
      <feDropShadow dx="0" dy="6" stdDeviation="6" flood-color="#7c3aed" flood-opacity="0.25"/>
    </filter>
    <filter id="glow3d">
      <feDropShadow dx="0" dy="2" stdDeviation="3" flood-color="#7c3aed" flood-opacity="0.5"/>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="860" height="400" fill="#0d1117" rx="16"/>

  <!-- ── CARD 1: Mobile ── -->
  <g filter="url(#cardShadow)">
    <rect x="20" y="20" width="190" height="170" rx="12" fill="url(#cardBg)" stroke="#7c3aed" stroke-width="1"/>
    <rect x="20" y="20" width="190" height="4" rx="2" fill="url(#purpleAccent)"/>
  </g>
  <text x="115" y="50" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="#a78bfa" letter-spacing="1">📱 MOBILE</text>
  <text x="35" y="74"  font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">React Native 0.78</text>
  <text x="35" y="95"  font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Pure Kotlin Android</text>
  <text x="35" y="116" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Jetpack Compose</text>
  <text x="35" y="137" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Android SDK</text>
  <text x="35" y="158" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">iOS / Xcode</text>
  <text x="35" y="179" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">TestFlight</text>

  <!-- ── CARD 2: Languages ── -->
  <g filter="url(#cardShadow)">
    <rect x="230" y="20" width="190" height="170" rx="12" fill="url(#cardBg)" stroke="#06b6d4" stroke-width="1"/>
    <rect x="230" y="20" width="190" height="4" rx="2" fill="#06b6d4"/>
  </g>
  <text x="325" y="50" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="#67e8f9" letter-spacing="1">💻 LANGUAGES</text>
  <text x="245" y="74"  font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">TypeScript</text>
  <text x="245" y="95"  font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Kotlin</text>
  <text x="245" y="116" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">JavaScript</text>
  <text x="245" y="137" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Core Java</text>
  <text x="245" y="158" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">SQL</text>
  <text x="245" y="179" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">HTML / CSS</text>

  <!-- ── CARD 3: State & Storage ── -->
  <g filter="url(#cardShadow)">
    <rect x="440" y="20" width="190" height="170" rx="12" fill="url(#cardBg)" stroke="#8b5cf6" stroke-width="1"/>
    <rect x="440" y="20" width="190" height="4" rx="2" fill="#8b5cf6"/>
  </g>
  <text x="535" y="50" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="#c4b5fd" letter-spacing="1">🗄️ STATE &amp; DATA</text>
  <text x="455" y="74"  font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Redux Toolkit</text>
  <text x="455" y="95"  font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">RTK Query</text>
  <text x="455" y="116" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">MMKV</text>
  <text x="455" y="137" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">SQLite</text>
  <text x="455" y="158" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">AsyncStorage</text>
  <text x="455" y="179" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Offline-First Arch</text>

  <!-- ── CARD 4: Security ── -->
  <g filter="url(#cardShadow)">
    <rect x="650" y="20" width="190" height="170" rx="12" fill="url(#cardBg)" stroke="#f59e0b" stroke-width="1"/>
    <rect x="650" y="20" width="190" height="4" rx="2" fill="#f59e0b"/>
  </g>
  <text x="745" y="50" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="#fcd34d" letter-spacing="1">🔐 SECURITY</text>
  <text x="665" y="74"  font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">TOTP 2FA (RFC 6238)</text>
  <text x="665" y="95"  font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">NFC Peer-to-Peer</text>
  <text x="665" y="116" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Google Sign-In</text>
  <text x="665" y="137" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Firebase Auth</text>
  <text x="665" y="158" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">PIN Lock</text>
  <text x="665" y="179" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">QR Code Exchange</text>

  <!-- ── CARD 5: Cloud & Backend ── -->
  <g filter="url(#cardShadow)">
    <rect x="20" y="210" width="190" height="170" rx="12" fill="url(#cardBg)" stroke="#ef4444" stroke-width="1"/>
    <rect x="20" y="210" width="190" height="4" rx="2" fill="#ef4444"/>
  </g>
  <text x="115" y="240" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="#fca5a5" letter-spacing="1">🔥 CLOUD</text>
  <text x="35" y="264" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Firebase Suite</text>
  <text x="35" y="285" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">FCM Push Notifications</text>
  <text x="35" y="306" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">REST APIs</text>
  <text x="35" y="327" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Node.js / MERN</text>
  <text x="35" y="348" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Razorpay Payments</text>
  <text x="35" y="369" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">React.js + MUI</text>

  <!-- ── CARD 6: Native APIs ── -->
  <g filter="url(#cardShadow)">
    <rect x="230" y="210" width="190" height="170" rx="12" fill="url(#cardBg)" stroke="#3DDC84" stroke-width="1"/>
    <rect x="230" y="210" width="190" height="4" rx="2" fill="#3DDC84"/>
  </g>
  <text x="325" y="240" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="#86efac" letter-spacing="1">🤖 NATIVE APIS</text>
  <text x="245" y="264" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">TelephonyManager</text>
  <text x="245" y="285" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">ContentProvider</text>
  <text x="245" y="306" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Foreground Services</text>
  <text x="245" y="327" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">NativeModule Bridge</text>
  <text x="245" y="348" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Notification Listener</text>
  <text x="245" y="369" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Dual-SIM Routing</text>

  <!-- ── CARD 7: Tools ── -->
  <g filter="url(#cardShadow)">
    <rect x="440" y="210" width="190" height="170" rx="12" fill="url(#cardBg)" stroke="#f97316" stroke-width="1"/>
    <rect x="440" y="210" width="190" height="4" rx="2" fill="#f97316"/>
  </g>
  <text x="535" y="240" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="#fdba74" letter-spacing="1">🛠️ TOOLS</text>
  <text x="455" y="264" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Git / GitHub</text>
  <text x="455" y="285" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Android Studio</text>
  <text x="455" y="306" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">VS Code</text>
  <text x="455" y="327" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Jest (TDD)</text>
  <text x="455" y="348" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">ESLint / Prettier</text>
  <text x="455" y="369" font-family="'Segoe UI',sans-serif" font-size="12" fill="#e2e8f0">Xcode / TestFlight</text>

  <!-- ── CARD 8: Open Source ── -->
  <g filter="url(#cardShadow)">
    <rect x="650" y="210" width="190" height="170" rx="12" fill="url(#cardBg)" stroke="#ec4899" stroke-width="1"/>
    <rect x="650" y="210" width="190" height="4" rx="2" fill="#ec4899"/>
  </g>
  <text x="745" y="240" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" fill="#f9a8d4" letter-spacing="1">📦 OPEN SOURCE</text>
  <text x="665" y="264" font-family="'Segoe UI',sans-serif" font-size="10.5" fill="#e2e8f0">react-native-dialpad</text>
  <text x="665" y="284" font-family="'Segoe UI',sans-serif" font-size="10.5" fill="#94a3b8">  ↳ Dialpad component</text>
  <text x="665" y="304" font-family="'Segoe UI',sans-serif" font-size="10.5" fill="#e2e8f0">shimmer-skeleton</text>
  <text x="665" y="324" font-family="'Segoe UI',sans-serif" font-size="10.5" fill="#94a3b8">  ↳ Reanimated 2 loader</text>
  <text x="665" y="344" font-family="'Segoe UI',sans-serif" font-size="10.5" fill="#e2e8f0">react-native-messager</text>
  <text x="665" y="364" font-family="'Segoe UI',sans-serif" font-size="10.5" fill="#94a3b8">  ↳ Native SMS bridge</text>
</svg>

</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--  GITHUB STATS  -->
<!-- ══════════════════════════════════════════════════════════ -->

## 📊 &nbsp;GitHub Stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=balram-01&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7c3aed&icon_color=7c3aed&text_color=ffffff&count_private=true"/>
&nbsp;&nbsp;
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=balram-01&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7c3aed&text_color=ffffff&langs_count=8"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=balram-01&theme=tokyonight&hide_border=true&background=0D1117&ring=7c3aed&fire=ff6b35&currStreakLabel=7c3aed&sideLabels=a78bfa&dates=64748b" alt="streak"/>

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=balram-01&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&row=1"/>

</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--  PUBLISHED APPS (SVG cards — self-contained)  -->
<!-- ══════════════════════════════════════════════════════════ -->

## 🚀 &nbsp;Published Android Apps

<div align="center">

<svg viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <linearGradient id="appCardBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1e1b4b"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="aquaGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#06b6d4"/>
      <stop offset="100%" stop-color="#3b82f6"/>
    </linearGradient>
    <linearGradient id="stepGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#10b981"/>
      <stop offset="100%" stop-color="#3DDC84"/>
    </linearGradient>
    <linearGradient id="statusGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7c3aed"/>
      <stop offset="100%" stop-color="#ec4899"/>
    </linearGradient>
    <filter id="appShadow">
      <feDropShadow dx="0" dy="4" stdDeviation="8" flood-color="#000000" flood-opacity="0.4"/>
    </filter>
  </defs>

  <rect width="860" height="200" fill="#0d1117" rx="16"/>

  <!-- ── AquaAlert card ── -->
  <g filter="url(#appShadow)">
    <rect x="15" y="15" width="263" height="170" rx="14" fill="url(#appCardBg)" stroke="#06b6d4" stroke-width="1.5"/>
    <rect x="15" y="15" width="263" height="5" rx="3" fill="url(#aquaGrad)"/>
  </g>
  <text x="35" y="48"  font-family="'Segoe UI',sans-serif" font-size="22">💧</text>
  <text x="62" y="44"  font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700" fill="#ffffff">AquaAlert</text>
  <text x="62" y="60"  font-family="'Segoe UI',sans-serif" font-size="10" fill="#67e8f9">Smart Water Reminder &amp; Tracker</text>
  <!-- Stats pills -->
  <rect x="35" y="72"  width="78" height="20" rx="10" fill="#06b6d4" fill-opacity="0.2"/>
  <text x="74"  y="86" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#67e8f9">⭐ 4.38 Rating</text>
  <rect x="121" y="72" width="90" height="20" rx="10" fill="#06b6d4" fill-opacity="0.2"/>
  <text x="166" y="86" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#67e8f9">📲 1,840+ Installs</text>
  <rect x="35"  y="98" width="82" height="20" rx="10" fill="#06b6d4" fill-opacity="0.2"/>
  <text x="76"  y="112" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#67e8f9">🌍 160 Countries</text>
  <rect x="125" y="98" width="82" height="20" rx="10" fill="#06b6d4" fill-opacity="0.2"/>
  <text x="166" y="112" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#67e8f9">🌐 20 Languages</text>
  <text x="35" y="138" font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">Kotlin + Jetpack · Global leaderboard</text>
  <text x="35" y="154" font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">10+ drink types · Adaptive reminders</text>
  <!-- Play Store badge -->
  <rect x="35" y="164" width="120" height="16" rx="8" fill="#3DDC84" fill-opacity="0.15"/>
  <text x="95" y="175" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#3DDC84">▶ Google Play Store</text>

  <!-- ── SmartStepCounter card ── -->
  <g filter="url(#appShadow)">
    <rect x="298" y="15" width="263" height="170" rx="14" fill="url(#appCardBg)" stroke="#3DDC84" stroke-width="1.5"/>
    <rect x="298" y="15" width="263" height="5" rx="3" fill="url(#stepGrad)"/>
  </g>
  <text x="318" y="48"  font-family="'Segoe UI',sans-serif" font-size="22">👟</text>
  <text x="345" y="44"  font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700" fill="#ffffff">Smart Step Counter</text>
  <text x="345" y="60"  font-family="'Segoe UI',sans-serif" font-size="10" fill="#86efac">100% Ad-Free Pedometer</text>
  <rect x="318" y="72"  width="68" height="20" rx="10" fill="#10b981" fill-opacity="0.2"/>
  <text x="352" y="86" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#86efac">🚫 Zero Ads</text>
  <rect x="394" y="72"  width="82" height="20" rx="10" fill="#10b981" fill-opacity="0.2"/>
  <text x="435" y="86" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#86efac">🗺️ GPS Map Mode</text>
  <rect x="318" y="98"  width="88" height="20" rx="10" fill="#10b981" fill-opacity="0.2"/>
  <text x="362" y="112" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#86efac">🔋 Battery Friendly</text>
  <rect x="414" y="98"  width="100" height="20" rx="10" fill="#10b981" fill-opacity="0.2"/>
  <text x="464" y="112" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#86efac">📊 Weekly Progress</text>
  <text x="318" y="138" font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">Kotlin + Jetpack Compose · HW sensor</text>
  <text x="318" y="154" font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">Calorie tracking · Daily step goals</text>
  <rect x="318" y="164" width="120" height="16" rx="8" fill="#3DDC84" fill-opacity="0.15"/>
  <text x="378" y="175" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#3DDC84">▶ Google Play Store</text>

  <!-- ── StatusDownloader card ── -->
  <g filter="url(#appShadow)">
    <rect x="581" y="15" width="263" height="170" rx="14" fill="url(#appCardBg)" stroke="#a78bfa" stroke-width="1.5"/>
    <rect x="581" y="15" width="263" height="5" rx="3" fill="url(#statusGrad)"/>
  </g>
  <text x="601" y="48"  font-family="'Segoe UI',sans-serif" font-size="22">📥</text>
  <text x="628" y="44"  font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700" fill="#ffffff">Status Downloader</text>
  <text x="628" y="60"  font-family="'Segoe UI',sans-serif" font-size="10" fill="#c4b5fd">Privacy-First Utility App</text>
  <rect x="601" y="72"  width="104" height="20" rx="10" fill="#7c3aed" fill-opacity="0.2"/>
  <text x="653" y="86" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#c4b5fd">🔒 Zero Data Collect</text>
  <rect x="713" y="72"  width="80" height="20" rx="10" fill="#7c3aed" fill-opacity="0.2"/>
  <text x="753" y="86" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#c4b5fd">📴 Fully Offline</text>
  <rect x="601" y="98"  width="85" height="20" rx="10" fill="#7c3aed" fill-opacity="0.2"/>
  <text x="643" y="112" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#c4b5fd">⚡ One-Tap Save</text>
  <rect x="694" y="98"  width="98" height="20" rx="10" fill="#7c3aed" fill-opacity="0.2"/>
  <text x="743" y="112" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#c4b5fd">🔐 No Cloud Upload</text>
  <text x="601" y="138" font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">Pure Kotlin · Local storage only</text>
  <text x="601" y="154" font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">Lightweight · Single-tap UX</text>
  <rect x="601" y="164" width="120" height="16" rx="8" fill="#3DDC84" fill-opacity="0.15"/>
  <text x="661" y="175" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#3DDC84">▶ Google Play Store</text>
</svg>

</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--  FEATURED PROJECTS (SVG timeline style)  -->
<!-- ══════════════════════════════════════════════════════════ -->

## 💼 &nbsp;Work Projects

<div align="center">

<svg viewBox="0 0 860 340" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <linearGradient id="projBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1e1b4b"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <filter id="projShadow">
      <feDropShadow dx="0" dy="4" stdDeviation="6" flood-color="#7c3aed" flood-opacity="0.2"/>
    </filter>
  </defs>

  <rect width="860" height="340" fill="#0d1117" rx="16"/>

  <!-- Vertical timeline line -->
  <line x1="430" y1="20" x2="430" y2="320" stroke="#7c3aed" stroke-width="1.5" stroke-dasharray="6,4" opacity="0.4"/>

  <!-- ── ConnectApp (top-left) ── -->
  <g filter="url(#projShadow)">
    <rect x="15" y="15" width="395" height="140" rx="12" fill="url(#projBg)" stroke="#7c3aed" stroke-width="1"/>
    <rect x="15" y="15" width="395" height="4" rx="2" fill="#7c3aed"/>
  </g>
  <text x="35" y="42"  font-family="'Segoe UI',sans-serif" font-size="13" font-weight="700" fill="#a78bfa">📞 ConnectApp — Pure Kotlin Android</text>
  <text x="35" y="60"  font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">Hesten Solutions  ·  Mar 2025–Present</text>
  <text x="35" y="80"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Full RN → Kotlin rewrite, lower latency</text>
  <text x="35" y="97"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· TOTP 2FA from scratch (RFC 6238)</text>
  <text x="35" y="114" font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· NFC P2P + QR contact sharing</text>
  <text x="35" y="131" font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Dual-SIM routing · VCF bulk import</text>
  <!-- Tags -->
  <rect x="35"  y="140" width="46" height="14" rx="7" fill="#7c3aed" fill-opacity="0.25"/>
  <text x="58"  y="150" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#a78bfa">Kotlin</text>
  <rect x="87"  y="140" width="36" height="14" rx="7" fill="#7c3aed" fill-opacity="0.25"/>
  <text x="105" y="150" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#a78bfa">NFC</text>
  <rect x="129" y="140" width="44" height="14" rx="7" fill="#7c3aed" fill-opacity="0.25"/>
  <text x="151" y="150" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#a78bfa">2FA</text>

  <!-- ── OceanFM (top-right) ── -->
  <g filter="url(#projShadow)">
    <rect x="450" y="15" width="395" height="140" rx="12" fill="url(#projBg)" stroke="#06b6d4" stroke-width="1"/>
    <rect x="450" y="15" width="395" height="4" rx="2" fill="#06b6d4"/>
  </g>
  <text x="470" y="42"  font-family="'Segoe UI',sans-serif" font-size="13" font-weight="700" fill="#67e8f9">🌊 OceanFM — Facility Management</text>
  <text x="470" y="60"  font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">Probus Software  ·  Mar 2024–Mar 2025</text>
  <text x="470" y="80"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Selfie attendance + Foreground Services</text>
  <text x="470" y="97"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Geofence buzzer with real-time MapView</text>
  <text x="470" y="114" font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· QR-code patrol checkpoint system</text>
  <text x="470" y="131" font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Offline-first SQLite checklist mgmt</text>
  <rect x="470" y="140" width="58" height="14" rx="7" fill="#06b6d4" fill-opacity="0.2"/>
  <text x="499"  y="150" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#67e8f9">RN + Kotlin</text>
  <rect x="534" y="140" width="46" height="14" rx="7" fill="#06b6d4" fill-opacity="0.2"/>
  <text x="557"  y="150" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#67e8f9">SQLite</text>

  <!-- ── Weldmate (bottom-left) ── -->
  <g filter="url(#projShadow)">
    <rect x="15" y="185" width="395" height="140" rx="12" fill="url(#projBg)" stroke="#f59e0b" stroke-width="1"/>
    <rect x="15" y="185" width="395" height="4" rx="2" fill="#f59e0b"/>
  </g>
  <text x="35" y="212"  font-family="'Segoe UI',sans-serif" font-size="13" font-weight="700" fill="#fcd34d">🛒 Weldmate — E-Commerce Platform</text>
  <text x="35" y="230"  font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">Hesten Solutions  ·  2025</text>
  <text x="35" y="250"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Razorpay payment gateway integration</text>
  <text x="35" y="267"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· On-device PDF invoice generation</text>
  <text x="35" y="284"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· FlashList + Reanimated carousel UX</text>
  <text x="35" y="301"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Debounced search · Price range filter</text>
  <rect x="35"  y="310" width="72" height="14" rx="7" fill="#f59e0b" fill-opacity="0.2"/>
  <text x="71"  y="320" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#fcd34d">React Native</text>
  <rect x="113" y="310" width="58" height="14" rx="7" fill="#f59e0b" fill-opacity="0.2"/>
  <text x="142" y="320" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#fcd34d">Razorpay</text>

  <!-- ── JustKolab (bottom-right) ── -->
  <g filter="url(#projShadow)">
    <rect x="450" y="185" width="395" height="140" rx="12" fill="url(#projBg)" stroke="#ec4899" stroke-width="1"/>
    <rect x="450" y="185" width="395" height="4" rx="2" fill="#ec4899"/>
  </g>
  <text x="470" y="212"  font-family="'Segoe UI',sans-serif" font-size="13" font-weight="700" fill="#f9a8d4">🤝 JustKolab — Social Collaboration</text>
  <text x="470" y="230"  font-family="'Segoe UI',sans-serif" font-size="10" fill="#94a3b8">Appclub Technologies  ·  Sep 2022–Mar 2024</text>
  <text x="470" y="250"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Zero → Production (Android + iOS)</text>
  <text x="470" y="267"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Instagram feed + Firebase Realtime chat</text>
  <text x="470" y="284"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· AdMob + YouTube + Spotify SDKs</text>
  <text x="470" y="301"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#e2e8f0">· Full React.js web version</text>
  <rect x="470" y="310" width="72" height="14" rx="7" fill="#ec4899" fill-opacity="0.2"/>
  <text x="506" y="320" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#f9a8d4">React Native</text>
  <rect x="548" y="310" width="54" height="14" rx="7" fill="#ec4899" fill-opacity="0.2"/>
  <text x="575" y="320" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="9" fill="#f9a8d4">Firebase</text>
</svg>

</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--  NPM PACKAGES  -->
<!-- ══════════════════════════════════════════════════════════ -->

## 📦 &nbsp;Open-Source npm Packages

<div align="center">

| Package | Description | Downloads |
|:--|:--|:--:|
| [**@balram_01/react-native-dialpad**](https://www.npmjs.com/package/@balram_01/react-native-dialpad) | 📞 Production-ready customizable dialpad component for React Native | ![npm](https://img.shields.io/npm/dt/@balram_01/react-native-dialpad?style=flat-square&color=7c3aed&label=downloads) |
| [**react-native-shimmer-skeleton**](https://www.npmjs.com/package/react-native-shimmer-skeleton) | ✨ Lightweight shimmer skeleton loader with Reanimated 2 animations | ![npm](https://img.shields.io/npm/dt/react-native-shimmer-skeleton?style=flat-square&color=06b6d4&label=downloads) |
| [**react-native-messager**](https://www.npmjs.com/package/react-native-messager) | 💬 Native Android SMS sending & inbox management bridged to React Native | ![npm](https://img.shields.io/npm/dt/react-native-messager?style=flat-square&color=ec4899&label=downloads) |

</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--  CONTRIBUTION ACTIVITY  -->
<!-- ══════════════════════════════════════════════════════════ -->

## 📈 &nbsp;Contribution Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=balram-01&bg_color=0D1117&color=7c3aed&line=7c3aed&point=a78bfa&area=true&area_color=7c3aed&hide_border=true" width="100%"/>
</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--  EDUCATION & CERTS  -->
<!-- ══════════════════════════════════════════════════════════ -->

## 🎓 &nbsp;Education & Certifications

<div align="center">

<svg viewBox="0 0 860 90" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <linearGradient id="eduBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1e1b4b"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="goldGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#f59e0b"/>
      <stop offset="100%" stop-color="#fbbf24"/>
    </linearGradient>
  </defs>
  <rect width="860" height="90" fill="#0d1117" rx="12"/>
  <!-- Education card -->
  <rect x="15" y="12" width="400" height="66" rx="10" fill="url(#eduBg)" stroke="#f59e0b" stroke-width="1"/>
  <rect x="15" y="12" width="400" height="4" rx="2" fill="url(#goldGrad)"/>
  <text x="35" y="38"  font-family="'Segoe UI',sans-serif" font-size="13" font-weight="700" fill="#fcd34d">🏛️ B.Tech — Computer Engineering</text>
  <text x="35" y="56"  font-family="'Segoe UI',sans-serif" font-size="11" fill="#94a3b8">Vishwakarma Institute of Information Technology (VIIT), Pune  ·  2019–2023</text>
  <text x="35" y="72"  font-family="'Segoe UI',sans-serif" font-size="12" font-weight="700" fill="#fcd34d">CGPA: 9.02 / 10.0  🏆</text>
  <!-- Cert 1 -->
  <rect x="430" y="12" width="200" height="66" rx="10" fill="url(#eduBg)" stroke="#7c3aed" stroke-width="1"/>
  <rect x="430" y="12" width="200" height="4" rx="2" fill="#7c3aed"/>
  <text x="530" y="35" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="#a78bfa">📜 CERTIFICATION</text>
  <text x="530" y="52" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#e2e8f0">Android Developer</text>
  <text x="530" y="67" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#e2e8f0">Bootcamp</text>
  <!-- Cert 2 -->
  <rect x="645" y="12" width="200" height="66" rx="10" fill="url(#eduBg)" stroke="#06b6d4" stroke-width="1"/>
  <rect x="645" y="12" width="200" height="4" rx="2" fill="#06b6d4"/>
  <text x="745" y="35" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="700" fill="#67e8f9">🚀 CERTIFICATION</text>
  <text x="745" y="52" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#e2e8f0">Martian Internship</text>
  <text x="745" y="67" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#e2e8f0">Program</text>
</svg>

</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--  CONNECT SECTION  -->
<!-- ══════════════════════════════════════════════════════════ -->

## 🤝 &nbsp;Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/balram01/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect%20with%20me-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:baliramshejal2001@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-Drop%20a%20Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/balram-01">
  <img src="https://img.shields.io/badge/GitHub-Follow%20Me-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

<!-- FOOTER QUOTE SVG -->
<svg viewBox="0 0 700 70" xmlns="http://www.w3.org/2000/svg" width="80%">
  <defs>
    <linearGradient id="quoteBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1e1b4b"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="quoteLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7c3aed"/>
      <stop offset="50%" stop-color="#06b6d4"/>
      <stop offset="100%" stop-color="#ec4899"/>
    </linearGradient>
  </defs>
  <rect width="700" height="70" fill="url(#quoteBg)" rx="12"/>
  <rect x="0" y="0" width="700" height="3" rx="2" fill="url(#quoteLine)"/>
  <rect x="0" y="67" width="700" height="3" rx="2" fill="url(#quoteLine)"/>
  <text x="350" y="24" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" fill="#94a3b8" font-style="italic">
    "I don't just write code —
  </text>
  <text x="350" y="44" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="11" fill="#94a3b8" font-style="italic">
    I architect experiences that live in people's pockets."
  </text>
  <text x="350" y="62" text-anchor="middle" font-family="'Segoe UI',sans-serif" font-size="10" fill="#7c3aed">— Baliram Shejal</text>
</svg>

</div>

<!-- ══ FOOTER WAVE (capsule-render — battle-tested) ══ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer" width="100%"/>
