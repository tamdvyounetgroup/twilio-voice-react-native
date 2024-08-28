<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@twilio/voice-react-native-sdk](./voice-react-native-sdk.md) &gt; [CallInvite](./voice-react-native-sdk.callinvite_interface.md) &gt; [on](./voice-react-native-sdk.callinvite_interface.on_1_methodsignature.md)

## CallInvite.on() method

Rejected event. Raised when the call invite has been rejected.

<b>Signature:</b>

```typescript
on(rejectedEvent: CallInvite.Event.Rejected, listener: CallInvite.Listener.Rejected): this;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  rejectedEvent | [CallInvite.Event.Rejected](./voice-react-native-sdk.callinvite_namespace.event_enum.md) | The raised event string. |
|  listener | [CallInvite.Listener.Rejected](./voice-react-native-sdk.callinvite_namespace.listener_namespace.rejected_typealias.md) | A listener function that will be invoked when the event is raised. |

<b>Returns:</b>

this

- The call invite object.

## Remarks

