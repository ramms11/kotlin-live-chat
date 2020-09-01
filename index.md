## Outline
```markdown
1. Create project in Android Studio
2. Add dependencies
3. Add resources to show data in list
4. 
5. 
6. 
7. 
8. 
```

### 1. Create project
Start with new android studio project choosing Empty Activity.
Give project and package name and select language Kotlin.
Minimum SDK as API 19: Kitkat and finish

```markdown

Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

### 2. Add project dependencies
gradle.build(Module: app)

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ramms11/kotlin-live-chat/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
