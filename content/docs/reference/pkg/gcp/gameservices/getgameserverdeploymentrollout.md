
---
title: "GetGameServerDeploymentRollout"
title_tag: "Function GetGameServerDeploymentRollout | Module gameservices | Package GCP"
meta_desc: "Explore the GetGameServerDeploymentRollout function of the gameservices module, including examples, input properties, output properties, and supporting types. Use this data source to get the rollout state. "
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

Use this data source to get the rollout state.

https://cloud.google.com/game-servers/docs/reference/rest/v1beta/GameServerDeploymentRollout



## Using GetGameServerDeploymentRollout {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getGameServerDeploymentRollout<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/gameservices/#GetGameServerDeploymentRolloutArgs">GetGameServerDeploymentRolloutArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/gameservices/#GetGameServerDeploymentRolloutResult">GetGameServerDeploymentRolloutResult</a></span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_game_server_deployment_rollout(</span><span class="nx">deployment_id</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetGameServerDeploymentRolloutResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupGameServerDeploymentRollout<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">args</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/v3/go/gcp/gameservices?tab=doc#LookupGameServerDeploymentRolloutArgs">LookupGameServerDeploymentRolloutArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/v3/go/gcp/gameservices?tab=doc#LookupGameServerDeploymentRolloutResult">LookupGameServerDeploymentRolloutResult</a></span>, error)</span></code></pre></div>

> Note: This function is named `LookupGameServerDeploymentRollout` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetGameServerDeploymentRollout </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Gameservices.GetGameServerDeploymentRolloutResult.html">GetGameServerDeploymentRolloutResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.GameServices.GetGameServerDeploymentRolloutArgs.html">GetGameServerDeploymentRolloutArgs</a></span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="deploymentid_csharp">
<a href="#deploymentid_csharp" style="color: inherit; text-decoration: inherit;">Deployment<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The deployment to get the rollout state from. Only 1 rollout must be associated with each deployment.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="deploymentid_go">
<a href="#deploymentid_go" style="color: inherit; text-decoration: inherit;">Deployment<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The deployment to get the rollout state from. Only 1 rollout must be associated with each deployment.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="deploymentid_nodejs">
<a href="#deploymentid_nodejs" style="color: inherit; text-decoration: inherit;">deployment<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The deployment to get the rollout state from. Only 1 rollout must be associated with each deployment.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="deployment_id_python">
<a href="#deployment_id_python" style="color: inherit; text-decoration: inherit;">deployment_<wbr>id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The deployment to get the rollout state from. Only 1 rollout must be associated with each deployment.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## GetGameServerDeploymentRollout Result {#result}

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="defaultgameserverconfig_csharp">
<a href="#defaultgameserverconfig_csharp" style="color: inherit; text-decoration: inherit;">Default<wbr>Game<wbr>Server<wbr>Config</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="deploymentid_csharp">
<a href="#deploymentid_csharp" style="color: inherit; text-decoration: inherit;">Deployment<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="gameserverconfigoverrides_csharp">
<a href="#gameserverconfigoverrides_csharp" style="color: inherit; text-decoration: inherit;">Game<wbr>Server<wbr>Config<wbr>Overrides</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getgameserverdeploymentrolloutgameserverconfigoverride">List&lt;Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override&gt;</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="id_csharp">
<a href="#id_csharp" style="color: inherit; text-decoration: inherit;">Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="name_csharp">
<a href="#name_csharp" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="project_csharp">
<a href="#project_csharp" style="color: inherit; text-decoration: inherit;">Project</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="defaultgameserverconfig_go">
<a href="#defaultgameserverconfig_go" style="color: inherit; text-decoration: inherit;">Default<wbr>Game<wbr>Server<wbr>Config</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="deploymentid_go">
<a href="#deploymentid_go" style="color: inherit; text-decoration: inherit;">Deployment<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="gameserverconfigoverrides_go">
<a href="#gameserverconfigoverrides_go" style="color: inherit; text-decoration: inherit;">Game<wbr>Server<wbr>Config<wbr>Overrides</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getgameserverdeploymentrolloutgameserverconfigoverride">[]Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="id_go">
<a href="#id_go" style="color: inherit; text-decoration: inherit;">Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="name_go">
<a href="#name_go" style="color: inherit; text-decoration: inherit;">Name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="project_go">
<a href="#project_go" style="color: inherit; text-decoration: inherit;">Project</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="defaultgameserverconfig_nodejs">
<a href="#defaultgameserverconfig_nodejs" style="color: inherit; text-decoration: inherit;">default<wbr>Game<wbr>Server<wbr>Config</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="deploymentid_nodejs">
<a href="#deploymentid_nodejs" style="color: inherit; text-decoration: inherit;">deployment<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="gameserverconfigoverrides_nodejs">
<a href="#gameserverconfigoverrides_nodejs" style="color: inherit; text-decoration: inherit;">game<wbr>Server<wbr>Config<wbr>Overrides</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getgameserverdeploymentrolloutgameserverconfigoverride">Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override[]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="id_nodejs">
<a href="#id_nodejs" style="color: inherit; text-decoration: inherit;">id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="name_nodejs">
<a href="#name_nodejs" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="project_nodejs">
<a href="#project_nodejs" style="color: inherit; text-decoration: inherit;">project</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="default_game_server_config_python">
<a href="#default_game_server_config_python" style="color: inherit; text-decoration: inherit;">default_<wbr>game_<wbr>server_<wbr>config</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="deployment_id_python">
<a href="#deployment_id_python" style="color: inherit; text-decoration: inherit;">deployment_<wbr>id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="game_server_config_overrides_python">
<a href="#game_server_config_overrides_python" style="color: inherit; text-decoration: inherit;">game_<wbr>server_<wbr>config_<wbr>overrides</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getgameserverdeploymentrolloutgameserverconfigoverride">List[Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="id_python">
<a href="#id_python" style="color: inherit; text-decoration: inherit;">id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="name_python">
<a href="#name_python" style="color: inherit; text-decoration: inherit;">name</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="project_python">
<a href="#project_python" style="color: inherit; text-decoration: inherit;">project</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Supporting Types


<h4 id="getgameserverdeploymentrolloutgameserverconfigoverride">Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#GetGameServerDeploymentRolloutGameServerConfigOverride">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/v3/go/gcp/gameservices?tab=doc#GetGameServerDeploymentRolloutGameServerConfigOverride">output</a> API doc for this type.
{{% /choosable %}}
{{% choosable language csharp %}}
> See the   <a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.GameServices.Outputs.GetGameServerDeploymentRolloutGameServerConfigOverride.html">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="configversion_csharp">
<a href="#configversion_csharp" style="color: inherit; text-decoration: inherit;">Config<wbr>Version</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="realmsselectors_csharp">
<a href="#realmsselectors_csharp" style="color: inherit; text-decoration: inherit;">Realms<wbr>Selectors</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getgameserverdeploymentrolloutgameserverconfigoverriderealmsselector">List&lt;Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override<wbr>Realms<wbr>Selector<wbr>Args&gt;</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="configversion_go">
<a href="#configversion_go" style="color: inherit; text-decoration: inherit;">Config<wbr>Version</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="realmsselectors_go">
<a href="#realmsselectors_go" style="color: inherit; text-decoration: inherit;">Realms<wbr>Selectors</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getgameserverdeploymentrolloutgameserverconfigoverriderealmsselector">[]Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override<wbr>Realms<wbr>Selector</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="configversion_nodejs">
<a href="#configversion_nodejs" style="color: inherit; text-decoration: inherit;">config<wbr>Version</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="realmsselectors_nodejs">
<a href="#realmsselectors_nodejs" style="color: inherit; text-decoration: inherit;">realms<wbr>Selectors</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getgameserverdeploymentrolloutgameserverconfigoverriderealmsselector">Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override<wbr>Realms<wbr>Selector[]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="config_version_python">
<a href="#config_version_python" style="color: inherit; text-decoration: inherit;">config_<wbr>version</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span id="realms_selectors_python">
<a href="#realms_selectors_python" style="color: inherit; text-decoration: inherit;">realms_<wbr>selectors</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getgameserverdeploymentrolloutgameserverconfigoverriderealmsselector">List[Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override<wbr>Realms<wbr>Selector<wbr>Args]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4 id="getgameserverdeploymentrolloutgameserverconfigoverriderealmsselector">Get<wbr>Game<wbr>Server<wbr>Deployment<wbr>Rollout<wbr>Game<wbr>Server<wbr>Config<wbr>Override<wbr>Realms<wbr>Selector</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#GetGameServerDeploymentRolloutGameServerConfigOverrideRealmsSelector">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/v3/go/gcp/gameservices?tab=doc#GetGameServerDeploymentRolloutGameServerConfigOverrideRealmsSelector">output</a> API doc for this type.
{{% /choosable %}}
{{% choosable language csharp %}}
> See the   <a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.GameServices.Outputs.GetGameServerDeploymentRolloutGameServerConfigOverrideRealmsSelector.html">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="realms_csharp">
<a href="#realms_csharp" style="color: inherit; text-decoration: inherit;">Realms</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="realms_go">
<a href="#realms_go" style="color: inherit; text-decoration: inherit;">Realms</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="realms_nodejs">
<a href="#realms_nodejs" style="color: inherit; text-decoration: inherit;">realms</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="realms_python">
<a href="#realms_python" style="color: inherit; text-decoration: inherit;">realms</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-gcp">https://github.com/pulumi/pulumi-gcp</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
	<dt>Notes</dt>
	<dd>This Pulumi package is based on the [`google-beta` Terraform Provider](https://github.com/hashicorp/terraform-provider-google-beta).</dd>
</dl>
