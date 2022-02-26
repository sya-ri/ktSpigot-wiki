# 導入

### リリースバージョン

:warning: 現在開発中です。`v1.0.0` がリリースされるまでスナップショットバージョンを使ってください。

### スナップショットバージョン

開発中のバージョンを試すことができます。リリースされるまでに変更される可能性があるので注意してください。

<details>

<summary>BungeeCord</summary>

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

</details>

<details>

<summary>Spigot</summary>

{% code title="build.gradle.kts" %}
```kts
repositories {
    maven(url = "https://s01.oss.sonatype.org/content/repositories/snapshots/")
}

dependencies {
    // 1.8.x
    implementation("dev.s7a:ktSpigot-v1_8:1.0.0-SNAPSHOT")

    // 1.9.x
    implementation("dev.s7a:ktSpigot-v1_9:1.0.0-SNAPSHOT")

    // 1.10.x
    implementation("dev.s7a:ktSpigot-v1_10:1.0.0-SNAPSHOT")

    // 1.11.x
    implementation("dev.s7a:ktSpigot-v1_11:1.0.0-SNAPSHOT")

    // 1.12.x
    implementation("dev.s7a:ktSpigot-v1_12:1.0.0-SNAPSHOT")

    // 1.13.x
    implementation("dev.s7a:ktSpigot-v1_13:1.0.0-SNAPSHOT")

    // 1.14.x
    implementation("dev.s7a:ktSpigot-v1_14:1.0.0-SNAPSHOT")

    // 1.15.x
    implementation("dev.s7a:ktSpigot-v1_15:1.0.0-SNAPSHOT")

    // 1.16.x
    implementation("dev.s7a:ktSpigot-v1_16:1.0.0-SNAPSHOT")

    // 1.17.x
    implementation("dev.s7a:ktSpigot-v1_17:1.0.0-SNAPSHOT")

    // 1.18.x
    implementation("dev.s7a:ktSpigot-v1_18:1.0.0-SNAPSHOT")
```
{% endcode %}

</details>

