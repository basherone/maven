# maven
maven 私库

maven { url "https://raw.github.com/basherone/maven/release/" }

ext {
    tweenVersion = '6.3.3';
}

classpath "aurelienribon:tweenengine:$tweenVersion"

compile "aurelienribon:tweenengine:$tweenVersion"
