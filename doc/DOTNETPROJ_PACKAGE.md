# DOTNET Project tags for publish package.

```xml
  <PropertyGroup>
    <Authors>JorgePinetta</Authors>
    <Company>puertaDigital</Company>
    <Copyright>puertaDigital</Copyright>
    <Description>
      {DESCRIPTION-LINE}
      {DESCRIPTION-LINE}
    </Description>
    <GeneratePackageOnBuild>true</GeneratePackageOnBuild>
    <PackageIcon>logopd-square.png</PackageIcon>
    <PackageId>puertaDigital.{COMPONENT-NAME}</PackageId>
    <PackageLicenseExpression>MIT</PackageLicenseExpression>
    <PackageLicenseFile></PackageLicenseFile>
    <PackageProjectUrl>https://github.com/puertaDigital/{COMPONENT-NAME}</PackageProjectUrl>
    <PackageReadmeFile>README.md</PackageReadmeFile>
    <PackageReleaseNotes>
      * 1.1.0
        - {DESCRIPTION-LINE}.
        - {DESCRIPTION-LINE}.
      * 1.0.0
        - {DESCRIPTION-LINE}.
    </PackageReleaseNotes>
    <PackageTags></PackageTags>
    <RepositoryType>git</RepositoryType>
    <RepositoryUrl>https://github.com/puertaDigital/{COMPONENT-NAME}</RepositoryUrl>
    <TargetFramework>net7.0</TargetFramework>
    <Version>1.0.0.0</Version>
  </PropertyGroup>

  ...

  <ItemGroup>
    <None Include="..\..\res\logopd-square.png" Pack="true" PackagePath="\"/>
    <None Include="README.md" Pack="true" PackagePath="\"/>
  </ItemGroup>
```