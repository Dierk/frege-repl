#Frege REPL#

This is the command line REPL for Frege. Frege code snippets can be entered on the prompt to get them evaluated.
In addition to Frege code, the following commands are supported:

<table>
<tr>
<th>Command</th>
<th>Description</th>
</tr>
<tr>
<td>:type &lt;expression&gt;</td>
<td>Display the type of an expression</td>
</tr>
<tr>
<td>:browse &lt;moduleName&gt;</td>
<td>Display the names in a module if a module name is provided otherwise display the names in the default REPL module</td>
</tr>
<tr>
<td>:java</td>
<td>View Java translation of last compiled Frege source</td>
</tr>
<tr>
<td>:{</td>
<td>Start multiline definitions</td>
</tr>
<tr>
<td>:}</td>
<td>End multiline definitions</td>
</tr>
<tr>
<td>:load &lt;url or file&gt;</td>
<td>Load Frege code snippets from an URL or file</td>
</tr>
<tr>
<td>:r</td>
<td>Reload the last script URL or file</td>
</tr>
<tr>
<td>:history</td>
<td>Display the source history for definitions in the default REPL module</td>
</tr>
<tr>
<td>:reset</td>
<td>Reset the REPL discarding all the evaluated scripts</td>
</tr>
<tr>
<td>:version</td>
<td>Display Frege version</td>
</tr>
<tr>
<td>:help &lt;name&gt;</td>
<td>Display the documentation for the given name. If the name is not provided, display this help message</td>
</tr>
<tr>
<td>:q or :quit</td>
<td>Quit REPL</td>
</tr>
</table>

##How to run?##
1. Download Frege REPL archive from [releases](https://github.com/Frege/frege-repl/releases).
2. Extract the archive
3. Run the following command: (JRE 7 or above required) <BR/>
   `java -jar frege-repl-<version>.jar` where `<version>` is the version number on the jar.

##Build from sources##

1. ```~/workspace$ git clone https://github.com/Frege/frege-interpreter.git```
2. ```~/workspace/frege-interpreter$ mvn install```
3. ```~/workspace$ git clone https://github.com/Frege/frege-repl.git```
4. ```~/workspace/frege-repl$ mvn install```
5. To run, ```~/workspace/frege-repl$ mvn exec:exec```
   
