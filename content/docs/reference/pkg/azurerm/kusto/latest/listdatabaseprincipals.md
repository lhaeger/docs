
---
title: "ListDatabasePrincipals"
title_tag: "Function ListDatabasePrincipals | Module kusto/latest | Package azurerm"
meta_desc: "Explore the ListDatabasePrincipals function of the kusto/latest module, including examples, input properties, output properties, and supporting types. "
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->




## Using ListDatabasePrincipals {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>listDatabasePrincipals<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azurerm/kusto/latest/#ListDatabasePrincipalsArgs">ListDatabasePrincipalsArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/azurerm/kusto/latest/#ListDatabasePrincipalsResult">ListDatabasePrincipalsResult</a></span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>list_database_principals(</span><span class="nx">cluster_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">database_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">resource_group_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> ListDatabasePrincipalsResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>ListDatabasePrincipals<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">args</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azurerm/sdk/go/azurerm/kusto/latest?tab=doc#ListDatabasePrincipalsArgs">ListDatabasePrincipalsArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-azurerm/sdk/go/azurerm/kusto/latest?tab=doc#ListDatabasePrincipalsResult">ListDatabasePrincipalsResult</a></span>, error)</span></code></pre></div>

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">ListDatabasePrincipals </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.AzureRM/Pulumi.AzureRM.Kusto/latest.ListDatabasePrincipalsResult.html">ListDatabasePrincipalsResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.AzureRM/Pulumi.AzureRM.Kusto.Latest.ListDatabasePrincipalsArgs.html">ListDatabasePrincipalsArgs</a></span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="clustername_csharp">
<a href="#clustername_csharp" style="color: inherit; text-decoration: inherit;">Cluster<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the Kusto cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="databasename_csharp">
<a href="#databasename_csharp" style="color: inherit; text-decoration: inherit;">Database<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the database in the Kusto cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_csharp">
<a href="#resourcegroupname_csharp" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the Kusto cluster.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="clustername_go">
<a href="#clustername_go" style="color: inherit; text-decoration: inherit;">Cluster<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the Kusto cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="databasename_go">
<a href="#databasename_go" style="color: inherit; text-decoration: inherit;">Database<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the database in the Kusto cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_go">
<a href="#resourcegroupname_go" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the Kusto cluster.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="clustername_nodejs">
<a href="#clustername_nodejs" style="color: inherit; text-decoration: inherit;">cluster<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the Kusto cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="databasename_nodejs">
<a href="#databasename_nodejs" style="color: inherit; text-decoration: inherit;">database<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the database in the Kusto cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_nodejs">
<a href="#resourcegroupname_nodejs" style="color: inherit; text-decoration: inherit;">resource<wbr>Group<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the Kusto cluster.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="cluster_name_python">
<a href="#cluster_name_python" style="color: inherit; text-decoration: inherit;">cluster_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the Kusto cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="database_name_python">
<a href="#database_name_python" style="color: inherit; text-decoration: inherit;">database_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the database in the Kusto cluster.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="resource_group_name_python">
<a href="#resource_group_name_python" style="color: inherit; text-decoration: inherit;">resource_<wbr>group_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the resource group containing the Kusto cluster.{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## ListDatabasePrincipals Result {#result}

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="value_csharp">
<a href="#value_csharp" style="color: inherit; text-decoration: inherit;">Value</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#databaseprincipalresponse">List&lt;Pulumi.<wbr>Azure<wbr>RM.<wbr>Kusto.<wbr>Latest.<wbr>Outputs.<wbr>Database<wbr>Principal<wbr>Response&gt;</a></span>
    </dt>
    <dd>{{% md %}}The list of Kusto database principals.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="value_go">
<a href="#value_go" style="color: inherit; text-decoration: inherit;">Value</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#databaseprincipalresponse">[]Database<wbr>Principal<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}The list of Kusto database principals.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="value_nodejs">
<a href="#value_nodejs" style="color: inherit; text-decoration: inherit;">value</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#databaseprincipalresponse">Database<wbr>Principal<wbr>Response[]</a></span>
    </dt>
    <dd>{{% md %}}The list of Kusto database principals.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="value_python">
<a href="#value_python" style="color: inherit; text-decoration: inherit;">value</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#databaseprincipalresponse">List[Database<wbr>Principal<wbr>Response]</a></span>
    </dt>
    <dd>{{% md %}}The list of Kusto database principals.{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Supporting Types


<h4 id="databaseprincipalresponse">Database<wbr>Principal<wbr>Response</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/azurerm/types/output/#DatabasePrincipalResponse">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-azurerm/sdk/go/azurerm/kusto/latest?tab=doc#DatabasePrincipalResponse">output</a> API doc for this type.
{{% /choosable %}}
{{% choosable language csharp %}}
> See the   <a href="/docs/reference/pkg/dotnet/Pulumi.AzureRM/Pulumi.AzureRM.Kusto.Latest.Outputs.DatabasePrincipalResponse.html">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="name_csharp">
<a href="#name_csharp" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal name.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="role_csharp">
<a href="#role_csharp" style="color: inherit; text-decoration: inherit;">Role</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal role.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="tenantname_csharp">
<a href="#tenantname_csharp" style="color: inherit; text-decoration: inherit;">Tenant<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The tenant name of the principal{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="type_csharp">
<a href="#type_csharp" style="color: inherit; text-decoration: inherit;">Type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal type.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="appid_csharp">
<a href="#appid_csharp" style="color: inherit; text-decoration: inherit;">App<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Application id - relevant only for application principal type.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="email_csharp">
<a href="#email_csharp" style="color: inherit; text-decoration: inherit;">Email</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal email if exists.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="fqn_csharp">
<a href="#fqn_csharp" style="color: inherit; text-decoration: inherit;">Fqn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal fully qualified name.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="name_go">
<a href="#name_go" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal name.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="role_go">
<a href="#role_go" style="color: inherit; text-decoration: inherit;">Role</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal role.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="tenantname_go">
<a href="#tenantname_go" style="color: inherit; text-decoration: inherit;">Tenant<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The tenant name of the principal{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="type_go">
<a href="#type_go" style="color: inherit; text-decoration: inherit;">Type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal type.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="appid_go">
<a href="#appid_go" style="color: inherit; text-decoration: inherit;">App<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Application id - relevant only for application principal type.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="email_go">
<a href="#email_go" style="color: inherit; text-decoration: inherit;">Email</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal email if exists.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="fqn_go">
<a href="#fqn_go" style="color: inherit; text-decoration: inherit;">Fqn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal fully qualified name.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="name_nodejs">
<a href="#name_nodejs" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal name.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="role_nodejs">
<a href="#role_nodejs" style="color: inherit; text-decoration: inherit;">role</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal role.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="tenantname_nodejs">
<a href="#tenantname_nodejs" style="color: inherit; text-decoration: inherit;">tenant<wbr>Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The tenant name of the principal{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="type_nodejs">
<a href="#type_nodejs" style="color: inherit; text-decoration: inherit;">type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal type.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="appid_nodejs">
<a href="#appid_nodejs" style="color: inherit; text-decoration: inherit;">app<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Application id - relevant only for application principal type.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="email_nodejs">
<a href="#email_nodejs" style="color: inherit; text-decoration: inherit;">email</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal email if exists.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="fqn_nodejs">
<a href="#fqn_nodejs" style="color: inherit; text-decoration: inherit;">fqn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Database principal fully qualified name.{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="name_python">
<a href="#name_python" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Database principal name.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="role_python">
<a href="#role_python" style="color: inherit; text-decoration: inherit;">role</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Database principal role.{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="tenant_name_python">
<a href="#tenant_name_python" style="color: inherit; text-decoration: inherit;">tenant_<wbr>name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The tenant name of the principal{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="type_python">
<a href="#type_python" style="color: inherit; text-decoration: inherit;">type</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Database principal type.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="app_id_python">
<a href="#app_id_python" style="color: inherit; text-decoration: inherit;">app_<wbr>id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Application id - relevant only for application principal type.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="email_python">
<a href="#email_python" style="color: inherit; text-decoration: inherit;">email</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Database principal email if exists.{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span id="fqn_python">
<a href="#fqn_python" style="color: inherit; text-decoration: inherit;">fqn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Database principal fully qualified name.{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-azurerm">https://github.com/pulumi/pulumi-azurerm</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>
