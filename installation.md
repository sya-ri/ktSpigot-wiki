# 導入

## リリースバージョン

:warning: 現在開発中です。`v1.0.0` がリリースされるまでスナップショットバージョンを使ってください。

## スナップショットバージョン

開発中のバージョンを試すことができます。リリースされるまでに変更される可能性があるので注意してください。

### Spigot

{% tabs %}
{% tab title="Gradle (Kotlin)" %}
{% code title="build.gradle.kts" %}
```kts
repositories {
    maven(url = "https://s01.oss.sonatype.org/content/repositories/snapshots/")
}

dependencies {
    implementation("dev.s7a:ktSpigot-v1_18:1.0.0-SNAPSHOT")
}
```
{% endcode %}
{% endtab %}

{% tab title="Gradle (Groovy)" %}
{% code title="build.gradle" %}
```groovy
repositories {
    maven {
        url 'https://s01.oss.sonatype.org/content/repositories/snapshots/'
    }
}

dependencies {
    implementation 'dev.s7a:ktSpigot-v1_18:1.0.0-SNAPSHOT'
}
```
{% endcode %}
{% endtab %}
{% endtabs %}

#### バージョン一覧

Minecraft のバージョン毎にライブラリが分かれています。使う環境に合わせて変更してください。

| Minecraft | バージョン            |   |
| --------- | ---------------- | - |
| `1.18.x`  | `ktSpigot-v1_18` |   |
| `1.17.x`  | `ktSpigot-v1_17` |   |
| `1.16.x`  | `ktSpigot-v1_16` |   |
| `1.15.x`  | `ktSpigot-v1_15` |   |
| `1.14.x`  | `ktSpigot-v1_14` |   |
| `1.13.x`  | `ktSpigot-v1_13` |   |
| `1.12.x`  | `ktSpigot-v1_12` |   |
| `1.11.x`  | `ktSpigot-v1_11` |   |
| `1.10.x`  | `ktSpigot-v1_10` |   |
| `1.9.x`   | `ktSpigot-v1_9`  |   |
| `1.8.x`   | `ktSpigot-v1_8`  |   |

### BungeeCord

{% tabs %}
{% tab title="Gradle (Kotlin)" %}
{% code title="build.gradle.kts" %}
```kts
repositories {
    maven(url = "https://s01.oss.sonatype.org/content/repositories/snapshots/")
}

dependencies {
    implementation("dev.s7a:ktSpigot-bungee:1.0.0-SNAPSHOT")
}
```
{% endcode %}
{% endtab %}

{% tab title="Gradle (Groovy)" %}
{% code title="build.gradle" %}
```groovy
repositories {
    maven {
        url 'https://s01.oss.sonatype.org/content/repositories/snapshots/'
    }
}

dependencies {
    implementation 'dev.s7a:ktSpigot-bungee:1.0.0-SNAPSHOT'
}
```
{% endcode %}
{% endtab %}
{% endtabs %}
