## What happened?

Since IntelliJ platform 2022.3, Rainbow Brackets has marked a "Freemium". Existing features before version 2022.3.1 are still FREE.

之前的功能仍然免费！只有新增加的高阶功能是付费的，不付费仍然可以使用。

All features which are inside GitHub are free to use unless it needs lots of time to develop(e.g. Supporting new languages, Supporting old frameworks, etc.).
Non-free features are flagged with [paid] inside the changelog.
A license can be bought at JetBrains Marketplace. And everyone has a 30 days trial license. Please try it before you buy it.
**If you already contributed to this project(by writing PR or financial contribution), you can get a free license by contacting me at izhangzhihao@hotmail.com**

## Paid features

| features                              | since  |
|---------------------------------------|--------|
| C# related files support              | 2022.3 |
| Indent highlighting advanced features | 2022.3 |
| Color generator options               | 2022.3 |
| Config up to 10 colors in config panel| 2022.3 |
| Color generator for rainbow varibeles | 2022.3 |


## What effect on me?

If your daily features are not in the Paid features list, you don't need to worry about it.
Otherwise, you can get a notification when you open a file that is not freely supported by this plugin.
You can try to get a 30 days trial license, which has all same features as the paid license.

## Future plans

Please check out [our plans for paid plugin](https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2538)

## Change log

<p>2022.3.5</p>
        <ul>
            <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2548">#2548: [Rainbow variables] Rainbow variables settings are not reflected.</a></li>
            <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2555">#2555: [Rainbow variables] Variables colors contrast too low for light theme.</a></li>
            <li>Add new options for color generator</li>
            <li>Color config panel support up to 10 colors</li>
        </ul>
        <br/>
<img width="749" alt="image" src="https://user-images.githubusercontent.com/12044174/202852094-2da6945b-598e-4def-ab0c-331abdd6d3f8.png">
<img width="680" alt="image" src="https://user-images.githubusercontent.com/12044174/202893817-4a88d0c8-1c9d-4442-86f1-235c2653cf60.png">

<p>2022.3.4</p>
        <ul>
            <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2551">#2551: [Rainbow variables] rainbow variable does not take effect after IDEA is restarted.</a></li>
            <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2549">#2549: Make 'enable rainbow variables' and 'rainbowify python keywords' can be checked both.</a></li>
        </ul>
        <br/>

<p>2022.3.3</p>
        <ul>
            <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2541">#2541: [Rainbow variables] Ask to enable rainbow variables before turn it on.</a></li>
        </ul>
        <br/>

<img width="383" alt="image" src="https://user-images.githubusercontent.com/12044174/200470979-3c507d0c-c838-4753-8435-a7cf879120a7.png">


<p>2022.3.2</p>
<ul>
  <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/380">#380: [paid][feature]
      Highlighted current rainbow indent guide lines.</a></li>
  <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2536">#2536: [paid][feature]
      Highlighted current rainbow indent guide lines.</a></li>
  <li>Feature: enable rainbow variables by default(Config the colors here: Editor -> Scheme -> Language Defaults ->
    Semantic Highlighting)</li>
</ul>
<br />

<img width="825" alt="image" src="https://user-images.githubusercontent.com/12044174/198984655-aedcec69-58c3-465f-b06a-279fd35068bd.png">

<img width="1108" alt="image" src="https://user-images.githubusercontent.com/12044174/198995710-a7956ae3-b008-41f0-a391-caf5a39cd8dd.png">

<img width="733" alt="image" src="https://user-images.githubusercontent.com/12044174/199013321-331a5597-5a8b-45c4-91c8-382e0ad7bbf6.png">

<p>2022.3.1</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2529">#2529: [paid][C#] fix:
            compatibility issues with Rider 2022.3.</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2533">#2533: [paid][C#] fix:
            colours incorrect when using "Cycle count on all brackets".</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2354">#2354: [paid][C#] fix:
            colours incorrect when using "Cycle count on all brackets".</a></li>
    <li>Fix many compatibility issues with IntelliJ platform 2022.3.</li>
</ul>
<br />

<img width="800" alt="image" src="https://user-images.githubusercontent.com/12044174/197786778-9d07ea50-154d-4efd-a70a-f454951b4ea6.png">

<p>6.26</p>
<ul>
    <li>Bump dependencies.</li>
</ul>
<br />

<p>6.25</p>
<ul>
    <li><a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/pull/2484">#2484 Add configurable threshold
            for number of lines for big files.</a></li>
</ul>
<br />

<p>6.24</p>
<ul>
    <li><a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2478">#2478 Scope highlighting not
            working with Hiberbee Theme(and other themes).</a></li>
</ul>
<br />

<p>6.23</p>
<ul>
    <li><a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2465">#2465 Improved performance of
            `annotateUtil`.</a></li>
</ul>
<br />

<p>6.22</p>
<ul>
    <li><a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2408">#2408 Support Code With Me
            client(Doesn't even need to be installed on the client side)</a></li>
</ul>
<br />

<p>6.21</p>
<ul>
    <li>Handle exceptions in `RainbowHighlightVisitor.analyze()`</a></li>
    <li>Cleanup 201.* stuff</a></li>
    <li>Refactoring</a></li>
    <li>Mirror changes from https://github.com/JetBrains/intellij-community</a></li>
    <li>Using textMatches instead of text to avoid expensive traverses the whole PSI tree & format code</a></li>
    <li>Add support for rainbowify Python keywords</li>
    <li>Compatible with DataSpell</li>
</ul>
<br />

<p>6.20</p>
<ul>
    <li>Handle exceptions in `RainbowHighlightVisitor.analyze()`</a></li>
    <li>Cleanup 201.* stuff</a></li>
    <li>Refactoring</a></li>
    <li>Mirror changes from https://github.com/JetBrains/intellij-community</a></li>
    <li>Using textMatches instead of text to avoid expensive traverses the whole PSI tree & format code</a></li>
    <li>Add support for rainbowify Python keywords</li>
    <li>Compatible with DataSpell</li>
</ul>
<br />

<p>6.19</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2280">#2280: [SQL] the END keyword
            is improperly detected as closing a BEGIN scope when the END actually closes a CASE.</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/1993">#1993: Change the default
            color schema in light theme.</a></li>
    <li>Nashorn Engine removed, compatible with JDK15+, tested with OpenJDK 17-ea+24 on MacBook Pro (16-inch, 2019) &
        IntelliJ IDEA 2021.2 Build #IU-212.4638.7</li>
    <li>Compatible with HUAWEI DevEco Studio</li>
</ul>
<br />

<p>6.18</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/2037">#2037: Wrong coloring in
            generic `<` after comparison operator `<`.</a>
    </li>
    <li>Error report removed.</li>
</ul>
<br />

<p>6.17</p>
<ul>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/pull/1068">#1068: @keeganwitt Add
            language exclusions to settings (closes #1046) (#1068) </a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/1067">#1067: Don't rainbowify big
            files notification annoying</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/1057">#1057: Wrong coloring in
            lambda expressions with braces</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/497">#497: Add `<` & `>` support
                for C# </a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/191">#191: C# Razor Pages
            (.cshtml) Support </a></li>
    <li>Deprecated API usage removed.</li>
</ul>
<br />

<p>6.16</p>
<ul>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/458">#458: Color Parentheses
            In Go Template</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/988">#988: (@Grandmother) minor:
            fix mispell in notification message</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/973">#973: File text mismatch</a>
    </li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/497">#497: C# in Rider - only
            squiggly brackets are rainbowified </a></li>
</ul>
<br />

<p>6.15</p>
<ul>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/897">#897: Initial support for
            Pug/Jade Language</a></li>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/830">#830: New option "Do NOT
            rainbowify template string"</a></li>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/784">#784: Disable rainbowify
            on big files(>1000 lines for now)</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/851">#851: Rainbowify tag name
            doesn't works in JSX</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/875">#875: cannot create
            configurable component</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/799">#799 #817: Wrong element
            created by ASTFactory</a></li>
</ul>
<br />

<p>6.13</p>
<ul>
    <li>Make as a non-dynamic plugin, so it now requires restart.</li>
</ul>
<br />

<p>6.12.1</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/516">#516: Add option to raibowify
            tag name of XML/HTML(disabled by default)</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/279">#279: Hide update
            notification on any click & Disable update notification support</a></li>
    <li>Feature: Rainbowify XML/HTML tag name.</li>
    <li>Feature: Upgrade to kotlin 1.4.10.</li>
</ul>
<br />

<p>6.12</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/279">#279: Hide update
            notification on any click & Disable update notification support</a></li>
    <li>Feature: Rainbowify XML/HTML tag name.</li>
    <li>Feature: Upgrade to kotlin 1.4.10.</li>
</ul>
<br />

<p>6.11</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/481">#481: rainbow-brackets does
            not support bash shell properly(for BashSupport Pro and Shell Script)</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/485">#485: Incorrect coloriziong
            after lambda in C#</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/242">#242: Colorization is applied
            only to left parenthesis in for loop(C#) </a></li>
    <li>Feature: C# support switch to new implementation.</li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/476">#476: Cannot create class
            com.github.izhangzhihao.rainbow.brackets.provider.SqlProvider</a></li>
</ul>
<br />

<p>6.10</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/480">#480: Plugin Incompatibility:
            Android Studio 4.2 Alpha 8</a></li>
</ul>
<br />

<p>6.9.1</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/445">#445: No working on Android
            Studio canary 4.2</a></li>
    <li>Some bug fixs and code refactorings</li>
</ul>
<br />

<p>6.7</p>
<ul>
    <li>Fix NPE</li>
</ul>
<br />

<p>6.6</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/436">#436: Duplicated indent
            guides in 2020.2 EAP</a></li>
</ul>
<br />

<p>6.5</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/410">#410:
            ArrayIndexOutOfBoundsException</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/429">#429:
            NullPointerException</a></li>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/427">#427: Colorizing angle
            brackets for Typescript generics</a></li>
    <li>Some refactoring!</li>
</ul>
<br />

<p>6.4</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/420">#420: Exceptions in random
            color generator</a></li>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/423">#423: Don't rainbow php and
            echo tag</a></li>
    <li>Fix anonymous feedback</li>
    <li>Some refactoring!</li>
</ul>
<br />

<p>6.3</p>
<ul>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/417">#417: Disable Rainbow
            Indents in Zen mode</a></li>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/227">#227: Coloring for angle
            bracket for C++ code</a></li>
    <li>Fix some exceptions and refactoring!</li>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/214">#214: New color generator
            to generate your color schema</a></li>
</ul>
<br />


<p>6.2</p>
<ul>
    <li>Fix <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/410">#410:
            ArrayIndexOutOfBoundsException when number of colors to less than 5</a></li>
</ul>
<br />

<p>6.1</p>
<ul>
    <li>First release of 2020.1 and Java 11!</li>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/235">#235: support SQL begin
            end colorization</a></li>
    <li>Notification improved</li>
    <li>Error report improved</li>
    <li>Deprecated API usage removed</li>
    <li>Initial support for <a
            href="https://www.jetbrains.org/intellij/sdk/docs/basics/plugin_structure/dynamic_plugins.html">dynamic
            plugin</a></li>
</ul>
<br />

<p>6.0</p>
<ul>
    <li>First release of 2020.1 and Java 11!</li>
    <li>Feature <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/issues/235">#235: support SQL begin
            end colorization</a></li>
    <li>Notification improved</li>
    <li>Error report improved</li>
    <li>Deprecated API usage removed</li>
    <li>Initial support for <a
            href="https://www.jetbrains.org/intellij/sdk/docs/basics/plugin_structure/dynamic_plugins.html">dynamic
            plugin</a></li>
</ul>
<br />

<p>5.35</p>
<ul>
    <li>Final release of 2017.2 and Java 8! start from the next release, we will build against with 2020.1 and Java 11
    </li>
</ul>
<br />

<p>5.34</p>
<ul>
    <li>Compatible with Material Theme UI Plugin</li>
    <li>Fix typo</li>
</ul>
<br />

<p>5.33</p>
<ul>
    <li>Fix ArrayIndexOutOfBoundsException</li>
</ul>
<br />

<p>5.32</p>
<ul>
    <li>Feature #391: Support cycle color on all bracket types(new option `Cycle count on all bracket types`)</li>
    <li>Fix ArrayIndexOutOfBoundsException</li>
</ul>
<br />

<p>5.31</p>
<ul>
    <li>#187 Feature: Ability to increase the number of colours in the IDE</li>
    <li>#247 Feature: Add a button to apply the color code to all kind of brackets</li>
    <li>#374 Feature: Add support for IntelliJ-Haskell</li>
    <li>Fix #54: Disable rainbow for mxml files</li>
    <li>Fix typo</li>
</ul>
<br />

<p>5.30</p>
<ul>
    <li>Rollback indent guides</li>
</ul>
<br />

<p>5.29</p>
<ul>
    <li>Compatible color schema with the latest version of material-theme-jetbrains</li>
    <li>Fix some errors</li>
</ul>
<br />

<p>5.28</p>
<ul>
    <li>Improve error report</li>
    <li>Fix some errors with Nginx plugin</li>
</ul>
<br />

<p>5.27</p>
<ul>
    <li>Improve rainbow indent guide lines</li>
</ul>
<br />

<p>5.26</p>
<ul>
    <li>Improve error report.</li>
</ul>
<br />

<p>5.25</p>
<ul>
    <li>Fix #259 Runtime error in rainbow indent guide lines.</li>
</ul>
<br />

<p>5.24</p>
<ul>
    <li>Fix #252 Runtime error in rainbow indent guide lines.</li>
    <li>Fix #254 Nginx support is been disabled from now on.</li>
    <li>Re-enable anonymous feedback</li>
</ul>
<br />

<p>5.23</p>
<ul>
    <li>#164 #251 New feature: Rainbow indent guide lines(experimental), Thanks https://github.com/YiiGuxing !</li>
</ul>
<br />

<p>5.22</p>
<ul>
    <li>Fix #243 #180, allow users custom matched brace by setting `overrideMatchedBraceAttributes = false`</li>
</ul>
<br />

<p>5.21</p>
<ul>
    <li>#65 [Scope Highlighting] now the effects will not been removed after shortcut released, users could press the
        key `ESC` to do this. There also have an option `Press any key to remove the highlighting effects`</li>
    <li>Refactoring & Remove dead code</li>
</ul>
<br />

<p>5.20</p>
<ul>
    <li>#233 Option to not rainbowify brackets of the first level</li>
    <li>#234 Color is displayed with wrong order in C# code</li>
</ul>
<br />

<p>5.19</p>
<ul>
    <li>Fix notification.</li>
</ul>
<br />

<p>5.18</p>
<ul>
    <li>Add notification for custom your own rainbow colors.</li>
</ul>
<br />

<p>5.17</p>
<ul>
    <li>More color options for squiggly brackets before cycle(#215).</li>
    <li>NullPointerException in while analyse code(#216).</li>
</ul>
<br />

<p>5.16</p>
<ul>
    <li>Add shiny new icon.</li>
</ul>
<br />

<p>5.15</p>
<ul>
    <li>Fix support for kotlin scheme attribute "KOTLIN_FUNCTION_LITERAL_BRACES_AND_ARROW".</li>
</ul>
<br />

<p>5.14</p>
<ul>
    <li>Remove deprecated API usages.</li>
    <li>Refactoring.</li>
    <li>Added Dart to the supported languages list(#205).</li>
</ul>
<br />

<p>5.13</p>
<ul>
    <li>Fix macro support of Clang(#198)</li>
    <li>Remove red-variation colors from default configuration(#192)</li>
</ul>
<br />

<p>5.12</p>
<ul>
    <li>Intellij-rainbow-brackets now support C# language(#6)!</li>
</ul>
<br />

<p>5.11</p>
<ul>
    <li>Now you could disable rainbow brackets for specific languages, see more info <a
            href="https://github.com/izhangzhihao/intellij-rainbow-brackets#disable-rainbow-brackets-for-specific-languages">here</a>.
    </li>
</ul>
<br />

<p>5.10</p>
<ul>
    <li>New color settings page!!! Thanks this PR(#179) from https://github.com/YiiGuxing.</li>
    <li>See the new settings page in Settings/Preferences > Editor > Color Scheme > Rainbow Brackets.</li>
</ul>
<br />

<p>5.9.1</p>
<ul>
    <li>Fix wrong background color on a light theme of "MATCHED_BRACE_ATTRIBUTES"(#155).</li>
</ul>
<br />

<p>5.9</p>
<ul>
    <li>Rainbow Kotlin lambda expression arrow(#142).</li>
    <li>Experimental feature: Highlight Kotlin label(#143).</li>
    <li>Override "MATCHED_BRACE_ATTRIBUTES".</li>
    <li>Improve configs & docs.</li>
    <li>Cleanup temp code & deprecated code.</li>
    <li>Remove anonymous feedback.</li>
</ul>
<br />

<p>5.8.3</p>
<ul>
    <li>Improve anonymous feedback</li>
</ul>
<br />

<p>5.8.2</p>
<ul>
    <li>Override kotlin plugin setting `KOTLIN_FUNCTION_LITERAL_BRACES_AND_ARROW` to empty so that we could
        rainbowify multiple level lambda expressions.
    </li>
</ul>
<br />

<p>5.8.1</p>
<ul>
    <li>Fix #67: Can't find resource for bundle java.util.PropertyResourceBundle, key version</li>
    <li>Improve anonymous feedback</li>
</ul>
<br />

<p>5.8</p>
<ul>
    <li>Feature #52 Flat out all text other than brackets on key (Alt + Button3) press. (via pull request#63)
    </li>
    <li>Feature #61 Change Highlight Current Scope Keymap to Ctrl + Button3 (Windows & Linux) or Meta+ Button3
        (Mac) (via pull request#63)
    </li>
    <li>Add anonymous feedback support</li>
</ul>
<br />

<p>5.7.1</p>
<ul>
    <li>Fix #60 :Exception in v5.7</li>
    <li>Experimental feature: Highlight current scope when Ctrl(Windows & Linux)/Meta(Mac) key pressed (feature
        #37 / pull request#59)
    </li>
</ul>
<br />

<p>5.7</p>
<ul>
    <li>Experimental feature: Highlight current scope when Ctrl(Windows & Linux)/Meta(Mac) key pressed (feature
        #37 / pull request#59)
    </li>
</ul>
<br />

<p>5.6</p>
<ul>
    <li>Performance improvement</li>
</ul>
<br />

<p>5.5</p>
<ul>
    <li>Fix #53 The closing brackets or keywords are not highlighted (Ruby & PHP)</li>
</ul>
<br />

<p>5.4</p>
<ul>
    <li>Fix #53 The closing brackets or keywords are not highlighted (Ruby & PHP)</li>
</ul>
<br />

<p>5.3</p>
<ul>
    <li>Improve angle bracket support for Groovy</li>
</ul>
<br />

<p>5.2</p>
<ul>
    <li>#48 Performance improvement</li>
    <li>#49 Fix images size</li>
</ul>
<br />

<p>5.1</p>
<ul>
    <li>#39 Enable rainbow html in js</li>
</ul>
<br />

<p>5.0</p>
<ul>
    <li>Finally, intellij-rainbow-brackets released version 5.0 with all RC features & bug fix</li>
    <li><b>Thanks for https://github.com/YiiGuxing, which helps move this plugin from `Annotator` to
            `HighlightVisitor`!</b></li>
    <li>Check more info at <a href="https://github.com/izhangzhihao/intellij-rainbow-brackets/pull/25">here</a>
    </li>
    <li>From 5.x series we didn't need specific implementations like java/scala/kotlin specific implementations
        in 3.x series anymore!
    </li>
    <br />
    <li>#13 Add test for dart support & add `DartAngleBracketProvider` for support dart angle brackets</li>
    <li>#18 where to customize brackets color? See the config guide in <a
            href="https://github.com/izhangzhihao/intellij-rainbow-brackets#Config-brackets-colors">here</a>
    </li>
    <li>Add test for #39</li>
    <li>#38 Add support for JSX (React)</li>
    <li>Fix #27 Settings no longer works</li>
    <li>#30 Adjust color: remove red, purple from color palettes, add some material design color to color
        palettes.
    </li>
    <li>#32 Add version info in setting page</li>
    <li>#31 Fix 'Enablement of round brackets enables all but angle brackets'</li>
    <li>#10 #2 Add setting to disable rainbow-ify brackets without content</li>
    <li>Show update notification after plugin updated</li>
    <li>Add a lot of tests</li>
    <li>Convert all java code to kotlin</li>
    <br />
    <li>And with much more features not documented in release notes.</li>
    <li>NOTE: this version are build against with IU-2017.2.7, but verified by IC-2017.2</li>
</ul>
<br />

<p>5.0-RC4</p>
<ul>
    <li>#10 #2 Add setting to disable rainbow-ify brackets without content</li>
    <li>Show update notification after plugin updated</li>
    <li>Add a lot of tests</li>
    <li>Convert all java code to kotlin</li>
    <li>NOTE: this version are build against with IU-2017.2.7, but verified by IC-2017.2</li>
</ul>
<br />

<p>5.0-RC3</p>
<ul>
    <li>#32 Add version info in setting page</li>
    <li>#31 Fix 'Enablement of round brackets enables all but angle brackets(#31)'</li>
</ul>
<br />

<p>5.0-RC2</p>
<ul>
    <li>#30 Adjust color: remove red, purple from color palettes, add some material design color to color
        palettes.
    </li>
</ul>
<br />

<p>5.0-RC1</p>
<ul>
    <li>Fix #27 Settings no longer works</li>
</ul>
<br />

<p>5.0-RC0</p>
<ul>
    <li>This is the first RC releases on 5.x series!</li>
    <li><b>Thanks for https://github.com/YiiGuxing, which helps move this plugin from `Annotator` to
            `HighlightVisitor`!</b></li>
    <li>Check more info at https://github.com/izhangzhihao/intellij-rainbow-brackets/pull/25</li>
    <li>This RC release has fantastic compatibility with previous release(3.x series).</li>
    <li>From 5.x series we didn't need specific implementations like java/scala/kotlin specific implementations
        in 3.x series anymore!
    </li>
    <li>And with much more features not documented in release notes.</li>
</ul>
<br />

<p>3.1</p>
<ul>
    <li>Add a specific implementation for PHP language</li>
</ul>
<br />

<p>3.0</p>
<ul>
    <li>Version 3.0 has been released, with all RC features & bug fix</li>
    <li>Fix #23 Inconsistent colors</li>
    <li>Fix #21 Wrong bracket colorization based on spaces</li>
    <li>Fix #19 Kotlin expression inside string bug</li>
    <li>Fix #12 Symbol less ">" is considered as a bracket even without leading "<"< /li>
    <li>Fix #11 Same level brackets should have same color</li>
    <li>And much more!</li>
    <li>Add specific implement for java/kotlin/scala/javascript</li>
    <li>Add example to help people add specific implementation for specific language!</li>
    <li>Check out README.md on github https://github.com/izhangzhihao/intellij-rainbow-brackets</li>
</ul>
<br />

<p>3.0-RC5</p>
<ul>
    <li>Adjust colors for default light theme. Thanks to https://github.com/YiiGuxing</li>
</ul>
<br />

<p>3.0-RC4</p>
<ul>
    <li>Add specific implement for java/kotlin/scala</li>
    <li>So now in java/kotlin/scala same level brackets should have same color.</li>
    <li>Fix: #19:Kotlin expression inside string bug</li>
</ul>
<br />

<p>3.0-RC2</p>
<ul>
    <li>Remove option for enable/disable rainbow for HTML/XML</li>
</ul>
<br />

<p>3.0-RC1</p>
<ul>
    <li>Add new setting page to control what/how to colorify:</li>
    <li>1. Add option to Enable/disable rainbow</li>
    <li>2. Add option to Enable rainbow for any unsupported languages</li>
    <li>3. Add option to Enable/disable rainbow for HTML/XML</li>
    <li>4. Add option to Enable/disable rainbow for round brackets</li>
    <li>5. Add option to Enable/disable rainbow for squiggly brackets</li>
    <li>6. Add option to Enable/disable rainbow for square brackets</li>
    <li>7. Add option to Enable/disable rainbow for angle brackets</li>
</ul>
<br />

<p>2.6</p>
<ul>
    <li>Add support for salesforce apex language, thanks for https://github.com/onisuly</li>
</ul>
<br />

<p>2.5</p>
<ul>
    <li>Fix Rust support, thanks for https://github.com/fst3a</li>
</ul>
<br />

<p>2.4</p>
<ul>
    <li>Add support for SQL</li>
</ul>
<br />

<p>2.3</p>
<ul>
    <li>Add support for HTML/XML</li>
</ul>
<br />

<p>2.2</p>
<ul>
    <li>Add support for C#</li>
</ul>
<br />

<p>2.1</p>
<ul>
    <li>New identifiable colors</li>
</ul>
<br />

<p>2.0</p>
<ul>
    <li>Rainbowify brackets faster!</li>
</ul>
<br />

<p>1.1</p>
<ul>
    <li>Support IntelliJ IDEA based IDEs version 14 and above</li>
</ul>
<br />

<p>1.0</p>
<ul>
    <li>Initial release</li>
</ul>