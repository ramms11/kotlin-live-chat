## Langkah - langkah untuk membuat aplikasi exoplayer & live chat :
```markdown
1. Create new Project di Android studio
2. Add dependencies and module / library exoplayer and firebase
3. Membuat SimpleExoPlayer instance.
4. Attach player ke view (for video output and user input).
5. mempersiapkan player dengan MediaSource untuk di play.
6. Release player jika selesai.
```

### 1. Membuat Project
Memulai dengan proyek studio android baru dengan memilih Empty Activity.
Beri nama proyek dan paket dan pilih bahasa Kotlin.
SDK Minimum sebagai API 19: Kitkat dan selesai

### 2. Memnambahkan project dependencies / library

pada, app > gradle.build(Module: app)

```markdown
// standard module
implementation fileTree(dir: 'libs', include: ['*.jar'])
implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlin_version"
implementation 'androidx.appcompat:appcompat:1.1.0'
implementation 'androidx.core:core-ktx:1.2.0'

// constraint layout module
implementation "androidx.constraintlayout:constraintlayout:2.0.0-beta4"

// exoplayer module
implementation 'com.google.android.exoplayer:exoplayer:2.11.4'

// firebase module
implementation 'com.google.firebase:firebase-core:17.5.0'
implementation 'com.google.firebase:firebase-database:19.4.0'
```

