# List of error codes

A list of Error codes dumped from the anime game

```cs
public enum ReportErrorCode
{
    // Fields
    public int value__; // 0x10
    public const ReportErrorCode None = 0;
    public const ReportErrorCode NETWORK_DISCONNECT_GOBACKHOME = 4001;
    public const ReportErrorCode NETWORK_RECONNECT_GATE_FAIL = 4002;
    public const ReportErrorCode NETWORK_CONNECT_CLIENT_NOT_NULL = 4003;
    public const ReportErrorCode NETWORK_CONNECT_CLIENT_INIT_FAIL = 4004;
    public const ReportErrorCode NETWORK_LOGIN_EXCEPTION = 4005;
    public const ReportErrorCode NETWORK_CONNECT_GATE_FAIL = 4006;
    public const ReportErrorCode NETWORK_DISCONNECT_STATE = 4007;
    public const ReportErrorCode NETWORK_SEND_PACKET_ERROR = 4008;
    public const ReportErrorCode NETWORK_RECEIVE_PACKET_ERROR = 4009;
    public const ReportErrorCode NETWORK_EXCEPTION = 4010;
    public const ReportErrorCode NETWORK_ERROR = 4011;
    public const ReportErrorCode DISPATCH_GLOBAL_GET_TIMEOUT = 4201;
    public const ReportErrorCode DISPATCH_GLOBAL_GET_ERROR = 4202;
    public const ReportErrorCode DISPATCH_GLOBAL_PARSE_EXCEPTION = 4203;
    public const ReportErrorCode DISPATCH_GLOBAL_PARSE_INVALID = 4204;
    public const ReportErrorCode DISPATCH_GLOBAL_CONFIG_PARSE_FAIL = 4205;
    public const ReportErrorCode DISPATCH_REGION_GET_TIMEOUT = 4206;
    public const ReportErrorCode DISPATCH_REGION_GET_ERROR = 4207;
    public const ReportErrorCode DISPATCH_REGION_PARSE_EXCEPTION = 4208;
    public const ReportErrorCode DISPATCH_REGION_PARSE_INVALID = 4209;
    public const ReportErrorCode DISPATCH_CONFIG_PARSE_EXCEPTION = 4210;
    public const ReportErrorCode DISPATCH_GLOBAL_CONFIG_PARSE_INVALID = 4211;
    public const ReportErrorCode DISPATCH_REGION_RSP_INVALID = 4212;
    public const ReportErrorCode DISPATCH_REGION_ERR_WITH_CODE = 4213;
    public const ReportErrorCode DISPATCH_REGION_DECRYPT_FAIL = 4214;
    public const ReportErrorCode DISPATCH_REGION_LOAD_PATCH_CONNECT_ERROR = 4215;
    public const ReportErrorCode LOGIN_TOKEN_GET_FAIL = 4301;
    public const ReportErrorCode LOGIN_PLAYER_LOGIN__FAIL = 4302;
    public const ReportErrorCode LOGIN_ENTER_SCENE_READY_FAIL = 4303;
    public const ReportErrorCode LOGIN_INIT_FINISH_FAIL = 4304;
    public const ReportErrorCode LOGIN_ENTER_SCENE_DONE_FAIL = 4305;
    public const ReportErrorCode LOGIN_POST_ENTER_SCENE_FAIL = 4306;
    public const ReportErrorCode LOGIN_ENTERTOKEN_INVALID = 4307;
    public const ReportErrorCode LOGIN_TASK_TIMEOUT = 4308;
    public const ReportErrorCode LOGIN_SEED_DERYPT_FAIL = 4309;
    public const ReportErrorCode LOGIN_GEN_RANDOM_FAIL = 4310;
    public const ReportErrorCode SDK_INIT_FAIL = 4401;
    public const ReportErrorCode SDK_LOGIN_FAIL = 4402;
    public const ReportErrorCode SDK_LOGOUT_FAIL = 4403;
    public const ReportErrorCode SDK_PAY_FAIL = 4404;
    public const ReportErrorCode SDK_GETTIER_FAIL = 4405;
    public const ReportErrorCode SDK_GET_MALLPRODUCT_FAIL = 4406;
    public const ReportErrorCode SDK_GET_BPPRODUCT_FAIL = 4407;
    public const ReportErrorCode SDK_HASPRODUCT_FAIL = 4408;
    public const ReportErrorCode Unknown = -9000;
    public const ReportErrorCode TimeOut = -9002;
    public const ReportErrorCode VerifyMd5OrFileSizeFailed = -9004;
    public const ReportErrorCode DiskFull = -9005;
    public const ReportErrorCode IOFailed = -9006;
    public const ReportErrorCode InvalidSavePath = -9007;
    public const ReportErrorCode InvalidRequest = -9008;
    public const ReportErrorCode Cancelled = -9009;
    public const ReportErrorCode FetchFileLengthFailed = -9010;
    public const ReportErrorCode DownloadLengthNotEqualToExpected = -9011;
    public const ReportErrorCode WebException_Success = -9100;
    public const ReportErrorCode WebException_NameResolutionFailure = -9101;
    public const ReportErrorCode WebException_ConnectFailure = -9102;
    public const ReportErrorCode WebException_ReceiveFailure = -9103;
    public const ReportErrorCode WebException_SendFailure = -9104;
    public const ReportErrorCode WebException_PipelineFailure = -9105;
    public const ReportErrorCode WebException_RequestCanceled = -9106;
    public const ReportErrorCode WebException_ProtocolError = -9107;
    public const ReportErrorCode WebException_ConnectionClosed = -9108;
    public const ReportErrorCode WebException_TrustFailure = -9109;
    public const ReportErrorCode WebException_SecureChannelFailure = -9110;
    public const ReportErrorCode WebException_ServerProtocolViolation = -9111;
    public const ReportErrorCode WebException_KeepAliveFailure = -9112;
    public const ReportErrorCode WebException_Pending = -9113;
    public const ReportErrorCode WebException_Timeout = -9114;
    public const ReportErrorCode WebException_ProxyNameResolutionFailure = -9115;
    public const ReportErrorCode WebException_UnknownError = -9116;
    public const ReportErrorCode WebException_MessageLengthLimitExceeded = -9117;
    public const ReportErrorCode WebException_CacheEntryNotFound = -9118;
    public const ReportErrorCode WebException_RequestProhibitedByCachePolicy = -9119;
    public const ReportErrorCode WebException_RequestProhibitedByProxy = -9120;
    public const ReportErrorCode NotSupportedException = -9201;
    public const ReportErrorCode NotAValidMethodOrArgumentException = -9202;
    public const ReportErrorCode AuthenticationOrDecryptionFailed = -9203;
    public const ReportErrorCode SharingViolation = -9204;
    public const ReportErrorCode CouldNotFindFile = -9205;
    public const ReportErrorCode AliveKeeperNotWorking = -9301;
    public const ReportErrorCode NextResMergeError = -9321;
    public const ReportErrorCode ResetAudioLangFileError = -9331;
    public const ReportErrorCode ApplyAudioDiffError = -9341;
    public const ReportErrorCode SaveDownloadLogError = -9351;
    public const ReportErrorCode OtherErrorInFilesDownloadManager = -9359;
    public const ReportErrorCode NotAllFilesInResVersionExist = -9901;
    public const ReportErrorCode NotAllFilesInDataVersionExist = -9902;
    public const ReportErrorCode NotAllFilesInSilenceVersionExist = -9903;
    public const ReportErrorCode CancelledByUser = -9904;
    public const ReportErrorCode CannotReachNetwork = -9905;
    public const ReportErrorCode CheckWritableFailed = -9906;
    public const ReportErrorCode NotEnoughSpace = -9907;
    public const ReportErrorCode VerifyMd5Failed = -9908;
    public const ReportErrorCode CopyRemoteVersionFileFailed = -9909;
    public const ReportErrorCode WriteRevisionFileFailed = -9910;
    public const ReportErrorCode DownloadRemoteVersionFileFailed = -9911;
    public const ReportErrorCode OverwriteOldFileFailed = -9912;
    public const ReportErrorCode DownloadStuck = -9913;
    public const ReportErrorCode NotAllDownloadFilesExist = -9991;
    public const ReportErrorCode DownloaderStatusFailed = -9992;
    public const ReportErrorCode DownloadUnexpectedException = -9999;
    public const ReportErrorCode AiStucked = 3000;
    public const ReportErrorCode AiLog = 3001;
    public const ReportErrorCode UploadLogError = 2000;
    public const ReportErrorCode SECError = 5000;
    public const ReportErrorCode Audio_NotDialogSpeechPoster = 6000;
    public const ReportErrorCode Audio_MissingDialogVoicePlugin = 6001;
}
```

## Contributing

If you know any of these error codes and know how to solve it. Feel free to update [`error_codes.json`](./error_codes.json) by creating a PR to help us improving the data.

### Credits

- [NickTheHuy](https://github.com/NickTheHuy) - for `dump.cs`
