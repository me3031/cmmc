# SC.3.187
Establish and manage cryptographic keys for cryptography employed in organizational systems.

##  cmk-backing-key-rotation-enabled
[cmk-backing-key-rotation-enabled](https://docs.aws.amazon.com/config/latest/developerguide/cmk-backing-key-rotation-enabled.html)

Guidance:
Enable key rotation to ensure that keys are rotated once they have reached the end of their crypto period.

##  kms-cmk-not-scheduled-for-deletion
[kms-cmk-not-scheduled-for-deletion](https://docs.aws.amazon.com/config/latest/developerguide/kms-cmk-not-scheduled-for-deletion.html)

Guidance:
To help protect data at rest, ensure necessary customer master keys (CMKs) are not scheduled for deletion in AWS Key Management Service (AWS KMS). Because key deletion is necessary at times, this rule can assist in checking for all keys scheduled for deletion, in case a key was scheduled unintentionally.
