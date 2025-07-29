---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalarbitsettraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ScalarBitSetTraits` Struct Template

<p>This class should be specialized by any integer type that is a union of bit values and the YAML representation is a flow sequence of strings. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename Enable = void&gt;
struct llvm::yaml::ScalarBitSetTraits&lt;T, Enable&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Description {#details}

<p>This class should be specialized by any integer type that is a union of bit values and the YAML representation is a flow sequence of strings.</p>


<p>For example:</p>



<pre><code> struct ScalarBitSetTraits&lt;MyFlags&gt; {
   static void bitset(IO &amp;io, MyFlags &amp;value) {
     io.bitSetCase(value, "big",   flagBig);
     io.bitSetCase(value, "flat",  flagFlat);
     io.bitSetCase(value, "round", flagRound);
   }
 };
</code></pre>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
