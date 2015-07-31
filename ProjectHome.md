# Lape #
Lape is a scripting engine with a Pascal derived syntax for Free Pascal and Delphi. It's written with speed and a broad platform compatibility in mind. The syntax is backwards compatible with Pascal Script (to a certain degree).
<br><br>
Lape is:<br>
<ul><li>A scripting engine<br>
</li><li>A Pascal derived language<br>
<ul><li><b>Basetypes</b>: Integers, Floats, Chars, Strings, Booleans, Variants, Arrays, Records, Unions, Enums, Sets, Pointers, Function pointers<br>
</li><li><b>Operations</b>: := = <> > >= < <= @ ^ + - <code>*</code> / <code>**</code> AND OR DIV XOR NOT IN SHL SHR<br>
</li><li><b>Constructs</b>: If, For, Case, Repeat, While, Try, Label<br>
</li><li>Internal and external (overloaded) functions (with support for default params)<br>
</li><li>Internal/external variables and constants (every variable is represented exactly as how it would be by FPC/Delphi)<br>
</li><li>Support for local (nested) declarations. So function can have their own constants/types/variables/functions.<br>
</li></ul></li><li>Portable<br>
<ul><li>Fully written in FPC/Delphi. No need for external libraries.<br>
</li><li>tested with Linux(x86/x64), Windows(x86/x64) and Mac OS, but supports virtually every platform FPC supports.<br>
</li></ul></li><li>Extensible<br>
<ul><li>New types can easily be added with specified behaviour for operations.<br>
</li><li>Optional foreign function interface which allows native calling of Lape functions and importing of functions without creating wrappers.<br>
</li></ul></li><li>Fast</li></ul>

<br><br><br>

<h2>Related Projects</h2>
<ul><li><a href='http://www.remobjects.com/ps.aspx'>Pascal Script</a> - This project started because Pascal Script is pretty slow and it didn't function very well on platforms other than Windows(x86).<br>
</li><li><a href='http://code.google.com/p/dwscript/'>DWScript</a> - This project started because DWScript didn't support pointers and dynamic arrays.