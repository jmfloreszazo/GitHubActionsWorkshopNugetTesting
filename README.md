# nuget.config

<?xml version="1.0" encoding="utf-8"?>
<configuration>
    <packageSources>
        <clear />
        <add key="github" value="https://nuget.pkg.github.com/YOUR_URI/index.json" />
    </packageSources>
    <packageSourceCredentials>
        <github>
            <add key="Username" value="YOUR_USER_TOKEN" />
            <add key="ClearTextPassword" value="YOUR_PRIVATE_TOKEN" />
        </github>
    </packageSourceCredentials>
</configuration>

