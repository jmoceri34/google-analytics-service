# Google Analytics Service for .NET

[![NuGet](https://img.shields.io/nuget/v/GoogleAnalyticsServiceForDotNet.svg)](https://www.nuget.org/packages/GoogleAnalyticsServiceForDotNet/) ![GitHub Workflow](https://github.com/joemoceri/google-analytics-service-dotnet/actions/workflows/dotnet.yml/badge.svg) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) (https://codecov.io/gh/joemoceri/google-analytics-service-dotnet) [![Build status](https://ci.appveyor.com/api/projects/status/i2in9jjivnh3oq43?svg=true)](https://ci.appveyor.com/project/joemoceri/google-analytics-service-dotnet) ![AppVeyor tests](https://img.shields.io/appveyor/tests/joemoceri/google-analytics-service-dotnet) ![GitHub repo size](https://img.shields.io/github/repo-size/joemoceri/google-analytics-service-dotnet) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/joemoceri/google-analytics-service-dotnet) ![Nuget](https://img.shields.io/nuget/dt/GoogleAnalyticsServiceForDotNet) ![GitHub Repo stars](https://img.shields.io/github/stars/joemoceri/google-analytics-service-dotnet?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/joemoceri/google-analytics-service-dotnet) ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/joemoceri/google-analytics-service-dotnet) 

# google-analytics-service-for-dotnet

This class serves as a wrapper around the Google Analytics v4 Reporting library found [here](https://www.nuget.org/packages/Google.Apis.AnalyticsReporting.v4). It uses service account credentials for access. You must provide these credentials yourself. This class will then accept a view id, start date, end date, dimensions, metrics, and return a C# [DataTable](https://docs.microsoft.com/en-us/dotnet/api/system.data.datatable) with the columns being the unique dimension combinations and the rows reflecting that. Please see the Sample project for more information.

**Quick Links**
- [Docs homepage](https://joemoceri.github.io/google-analytics-service-dotnet/)
- [Articles](https://joemoceri.github.io/google-analytics-service-dotnet/articles/Installation.html)
- [API Documentation](https://joemoceri.github.io/google-analytics-service-dotnet/api/index.html)
- [Examples](https://joemoceri.github.io/google-analytics-service-dotnet/articles/Examples.html)
