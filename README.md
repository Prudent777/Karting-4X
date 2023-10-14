# Karting-4X
<?xml version="1.0" encoding="utf-8"?>
<Project ToolsVersion="4.0" DefaultTargets="Build" xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
  <PropertyGroup>
	<Configuration Condition=" '$(Configuration)' == '' ">Debug</Configuration>
	<Platform Condition=" '$(Platform)' == '' ">AnyCPU</Platform>
	<ProductVersion>10.0.20506</ProductVersion>
	<SchemaVersion>2.0</SchemaVersion>
	<ProjectGuid>{5D3275F8-59FA-AD17-A373-B0D3F3BB239A}</ProjectGuid>
	<OutputType>Library</OutputType>
	<AppDesignerFolder>Properties</AppDesignerFolder>
	<RootNamespace></RootNamespace>
	<AssemblyName>Assembly-CSharp-Editor</AssemblyName>
	<TargetFrameworkVersion>v3.5</TargetFrameworkVersion>
	<FileAlignment>512</FileAlignment>
	<BaseDirectory>Assets</BaseDirectory>
  </PropertyGroup>
  <PropertyGroup Condition=" '$(Configuration)|$(Platform)' == 'Debug|AnyCPU' ">
	<DebugSymbols>true</DebugSymbols>
	<DebugType>full</DebugType>
	<Optimize>false</Optimize>
	<OutputPath>Temp\bin\Debug\</OutputPath>
	<DefineConstants>DEBUG;TRACE;UNITY_5_0_0;UNITY_5_0;UNITY_5;ENABLE_LICENSE_RENAME;ENABLE_NEW_BUGREPORTER;ENABLE_2D_PHYSICS;ENABLE_4_6_FEATURES;ENABLE_AUDIO;ENABLE_CACHING;ENABLE_CLOTH;ENABLE_FRAME_DEBUGGER;ENABLE_GENERICS;ENABLE_HOME_SCREEN;ENABLE_IMAGEEFFECTS;ENABLE_LIGHT_PROBES_LEGACY;ENABLE_MICROPHONE;ENABLE_MULTIPLE_DISPLAYS;ENABLE_NEW_HIERARCHY;ENABLE_PHYSICS;ENABLE_PHYSICS_PHYSX3;ENABLE_PLUGIN_INSPECTOR;ENABLE_SHADOWS;ENABLE_SINGLE_INSTANCE_BUILD_SETTING;ENABLE_SPRITES;ENABLE_TERRAIN;ENABLE_UNITYEVENTS;ENABLE_WEBCAM;ENABLE_WWW;ENABLE_AUDIOMIXER_SUSPEND;ENABLE_NONPRO;INCLUDE_DYNAMIC_GI;INCLUDE_GI;INCLUDE_IL2CPP;PLATFORM_SUPPORTS_MONO;RENDER_SOFTWARE_CURSOR;UNITY_ANDROID;UNITY_ANDROID_API;ENABLE_SUBSTANCE;ENABLE_TEXTUREID_MAP;ENABLE_EGL;ENABLE_NETWORK;ENABLE_RUNTIME_GI;ENABLE_MONO;ENABLE_PROFILER;UNITY_EDITOR;UNITY_EDITOR_64;UNITY_EDITOR_WIN;CROSS_PLATFORM_INPUT;MOBILE_INPUT;ENABLE_DUCK_TYPING</DefineConstants>
	<ErrorReport>prompt</ErrorReport>
	<WarningLevel>4</WarningLevel>
	<NoWarn>0169</NoWarn>
  </PropertyGroup>
  <PropertyGroup Condition=" '$(Configuration)|$(Platform)' == 'Release|AnyCPU' ">
	<DebugType>pdbonly</DebugType>
	<Optimize>true</Optimize>
	<OutputPath>Temp\bin\Release\</OutputPath>
	<DefineConstants>TRACE</DefineConstants>
	<ErrorReport>prompt</ErrorReport>
	<WarningLevel>4</WarningLevel>
	<NoWarn>0169</NoWarn>
  </PropertyGroup>
  <ItemGroup>
	<Reference Include="System" />
    <Reference Include="System.XML" />
	<Reference Include="System.Core" />
	<Reference Include="System.Xml.Linq" />
	<Reference Include="UnityEngine">
	  <HintPath>C:/Program Files/Unity/Editor/Data/Managed/UnityEngine.dll</HintPath>
	</Reference>
	<Reference Include="UnityEditor">
	  <HintPath>C:/Program Files/Unity/Editor/Data/Managed/UnityEditor.dll</HintPath>
	</Reference>
  </ItemGroup>
  <ItemGroup>
     <Compile Include="Assets\Pixel Map Terrain\Scripts\Editor\CreateTextAsset.cs" />
     <Compile Include="Assets\Pixel Map Terrain\Scripts\Editor\PixelMapTerrainEditor.cs" />
     <None Include="Assets\Pixel Map Terrain\README.txt" />
 <Reference Include="UnityEngine.UI">
 <HintPath>C:/Program Files/Unity/Editor/Data/UnityExtensions/Unity/GUISystem/UnityEngine.UI.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.Graphs">
 <HintPath>C:/Program Files/Unity/Editor/Data/Managed/UnityEditor.Graphs.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.Android.Extensions">
 <HintPath>C:/Program Files/Unity/Editor/Data/PlaybackEngines/androidplayer/UnityEditor.Android.Extensions.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.iOS.Extensions">
 <HintPath>C:/Program Files/Unity/Editor/Data/PlaybackEngines/iossupport/UnityEditor.iOS.Extensions.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.WP8.Extensions">
 <HintPath>C:/Program Files/Unity/Editor/Data/PlaybackEngines/wp8support/UnityEditor.WP8.Extensions.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.Metro.Extensions">
 <HintPath>C:/Program Files/Unity/Editor/Data/PlaybackEngines/metrosupport/UnityEditor.Metro.Extensions.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.BB10.Extensions">
 <HintPath>C:/Program Files/Unity/Editor/Data/PlaybackEngines/blackberryplayer/UnityEditor.BB10.Extensions.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.WebGL.Extensions">
 <HintPath>C:/Program Files/Unity/Editor/Data/PlaybackEngines/webglsupport/UnityEditor.WebGL.Extensions.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.LinuxStandalone.Extensions">
 <HintPath>C:/Program Files/Unity/Editor/Data/PlaybackEngines/linuxstandalonesupport/UnityEditor.LinuxStandalone.Extensions.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.WindowsStandalone.Extensions">
 <HintPath>C:/Program Files/Unity/Editor/Data/PlaybackEngines/windowsstandalonesupport/UnityEditor.WindowsStandalone.Extensions.dll</HintPath>
 </Reference>
 <Reference Include="UnityEditor.OSXStandalone.Extensions">
 <HintPath>C:/Program Files/Unity/Editor/Data/PlaybackEngines/macstandalonesupport/UnityEditor.OSXStandalone.Extensions.dll</HintPath>
 </Reference>
  </ItemGroup>
  <ItemGroup>
    <ProjectReference Include="Assembly-CSharp-vs.csproj">
      <Project>{23C1A763-8A84-2B22-82A9-1E218739A5B0}</Project>      <Name>Assembly-CSharp-vs</Name>    </ProjectReference>
  </ItemGroup>
  <Import Project="$(MSBuildToolsPath)\Microsoft.CSharp.targets" />
  <!-- To modify your build process, add your task inside one of the targets below and uncomment it. 
	   Other similar extension points exist, see Microsoft.Common.targets.
  <Target Name="BeforeBuild">
  </Target>
  <Target Name="AfterBuild">
  </Target>
  -->
  
</Project>
