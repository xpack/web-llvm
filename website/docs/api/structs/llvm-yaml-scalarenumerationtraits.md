---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalarenumerationtraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ScalarEnumerationTraits` Struct Template

<p>This class should be specialized by any integral type that converts to/from a YAML scalar where there is a one-to-one mapping between in-memory values and a string in YAML. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename Enable = void&gt;
struct llvm::yaml::ScalarEnumerationTraits&lt;T, Enable&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Description {#details}

<p>This class should be specialized by any integral type that converts to/from a YAML scalar where there is a one-to-one mapping between in-memory values and a string in YAML.</p>


<p>For example:</p>



<pre><code>struct ScalarEnumerationTraits&lt;Colors&gt; {
    static void enumeration(IO &amp;io, Colors &amp;value) {
      io.enumCase(value, "red",   cRed);
      io.enumCase(value, "blue",  cBlue);
      io.enumCase(value, "green", cGreen);
    }
  };
</code></pre>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
