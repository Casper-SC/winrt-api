---
-api-id: P:Windows.ApplicationModel.ConversationalAgent.ConversationalAgentSignal.SignalStart
-api-type: winrt property
ms.custom: 19H1
---

<!-- Property syntax.
public TimeSpan SignalStart { get;  set; }
-->

# Windows.ApplicationModel.ConversationalAgent.ConversationalAgentSignal.SignalStart

## -description

Gets or sets the time span of the [ConversationalAgentSignal](conversationalagentsignal.md) start.

## -property-value

## -remarks

If the [SignalStart](conversationalagentsignal_signalstart.md) and [SignalEnd](conversationalagentsignal_signalend.md) time spans are the same, this indicates that the signal is not a voice activation (for example, a keyboard press or Bluetooth activation).

If the [SignalStart](conversationalagentsignal_signalstart.md) and [SignalEnd](conversationalagentsignal_signalend.md) time spans are different, they indicate the position of the *wake* utterance in the audio stream.

## -see-also

## -examples
