# ColoredTextView
Un nuevo tipo de textView que tiene funciones de span ya listas en java

## ¿como usarlo?
en settings de gradle
```gradle
dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}
```
y en las dependencias
```gradle
dependencies {
    implementation 'com.github.RafacraftDev:ColoredTextView:1.0'
}
```
y en el java
```java
color.changeText("hello, world!"); // texto
color.setColor(0xFFFFFFFF); // color de texto sin span
color.setColors(new String[]{ "hello!" }, new int[] { 0xFFFF0000 }); // textos y colores
```

### creado por RafacraftCoder!
