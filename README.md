# school-pdf-portal
The source code that generated this unhandled exception can only be shown when compiled in debug mode. To enable this, please follow one of the below steps, then request the URL:

1. Add a "Debug=true" directive at the top of the file that generated the error. Example:

<%@ Page Language="C#" Debug="true" %>

or:

2) Add the following section to the configuration file of your application:

<configuration>

<system.web>

<compilation debug="true" />

</system.web>

</configuration>

Note that this second technique will cause all files within a given application to be compiled in debug mode. The first technique will cause only that particular file to be compiled in debug mode.

Important: Running applications in debug mode does incur a memory/performance overhead. You should make sure that an application has debugging disabled before deploying into production scenario.





ViewStateException: Invalid

viewstate.

Client IP:

110.227.61.186

Port: 48942

Referer:

https://vikuniexam.in/UG_NEP_RE

SULT.aspx

Path:

/UG_NEP_RESULT.aspx

User-Agent: Mozilla/5.0

(Linux; Android 10; K)

AppleWebKit/537.36 (KHTML, like Gecko) Chrome/154.0.0.0 Mobile Safari/537.36

ViewState:

U/6K/oPxEC6D3rfWAvKNVk820rzUFd+ y/wx1AT3PFdyRJYQPqbaBsLfxAp+Yr6 ReMWiMISf1BMZF2ur/1T7kZDw0o1pP+ 8h1Hbrx25zqkooEeehTLs9Q3nGtLqcy JzQXPcggqDlPJkx/mC79D4ZNNe9A8wL wltNpIr4NF44XSf8hnWaBtu8mKEH3Ka hw2GkYWBGw4Mm1a6m2PAzN7lIwuScTK 1cU7ci9bVYEQjEAcS7Yo3ItEdYy6NZM o39ta0Nw2ssUFwf2fLouzoA2S8bHa+C 8f/XBkSBKVTJ07aN3qPcO8RrzrvLJ/v QsBrKIFUqnFU9qqoptRGK8yHCRiioST YDA87YIvT30SVS/1QBdG2JUXUtARcDh kmMfu5qSHNGD1+kmCz7A0Cu39IX92LB DLOpiS1mb0fF2P7r+/R/+FZ6ZCXNnAB 7Jt3vfKteYGLPQ0fhxQ48SREDMq21CF HIG4D19ubr+akQAhjAwQabNDQgR3r1R 2ifHhCefP5CTOZZJCSL10gqYcTPKAju oSwtmlXfE1SCc2/dHLZv3cIH/w8MsSC zjiTKM5vjz+Ci/9TrKyFnFlL+3cx4Pm SYRTJXf87EQMx+ABVrLHuLgp7/xsD/+ eytlUjKuC/CjFmqIBPQ7+dUUnucTywW EkouFrnhH3126pyw9N0XMINNf3hugZK OEFdvb3JIj9b8xniE6JEEL512+51s+Q wMwW+r10020p45JVOwS2Hty0yihklAp
2deHnFaWsCCf4qu...]

[HttpException (0x80004005): Validation of viewstate MAC failed. If this application is hosted by a Web Farm or cluster, ensure that <machineKey> configuration specifies the same validationKey and validation algorithm. AutoGenerate cannot be used in a cluster.

See http://go.microsoft.com/fwlink/?LinkID=314055 for more information.]

System.Web.UI.ViewStateExceptio n. ThrowError (Exception inner, String persistedState, String errorPageMessage, Boolean macValidationError) +161

System.Web.UI.ObjectStateFormat ter. Deserialize(String inputString, Purpose purpose) +731

System.Web.UI. Util.DeserializeW ithAssert(IStateFormatter2 formatter, String serializedState, Purpose purpose) +65

System.Web.UI.HiddenFieldPageSt atePersister. Load() +319

System.Web.UI.Page. LoadPageStat eFromPersistenceMedium() +377
System.Web.UI.Page.ProcessReque stMain(Boolean includeStagesBeforeAsyncPoint, Boolean includeStages AfterAsyncPoint) +9298

System.Web.UI.Page.ProcessReque st(Boolean includeStages BeforeAsyncPoint, Boolean includeStages AfterAsyncPoint) +355

System.Web.UI.Page.ProcessReque st() +79

System.Web.UI.Page.ProcessReque st(HttpContext context) +74

ASP.ug_nep_result_aspx.ProcessR equest(HttpContext context) +46

System.Web.CallHandlerExecution Step.System.Web.HttpApplication .IExecutionStep.Execute() +537

System.Web.HttpApplication.Exec uteStepImpl(IExecutionStep step) +172

System.Web.HttpApplication.Exec uteStep (IExecutionStep step, Boolean& completedSynchronously) +93