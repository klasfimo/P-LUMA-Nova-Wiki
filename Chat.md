# Chat

P-LUMA keeps the vanilla chat. Its position, width, scale and opacity still come from Minecraft's own chat
settings. What P-LUMA adds is on the **Chat** page of the settings hub.

## Chat search

A magnifier sits at the right end of the chat input, following vanilla's chat opacity.

- Results appear where chat normally is, in the same style, newest at the bottom
- Matches are highlighted as you type
- **Click** a line to copy it to the clipboard
- **Shift + click** a line to insert it into the chat input
- **Esc** goes back to chat

Search covers everything in your chat history, so it works best with a longer history (below).

## Longer history

Vanilla keeps the last 100 chat lines. P-LUMA's history setting (on by default) lifts that.

| Setting | Range | Default |
|---|---|---|
| MoreChatHistory | on / off | On |
| Unlimited history | on / off | Off |
| History limit | 100 – 10,000 lines | 1,000 |

With **Unlimited history**, the session's chat stays scrollable and searchable up to 50,000 lines. That is
far beyond a normal session; the ceiling only stops a client left running for days on a busy server from
using more and more memory.

## Keep across servers

| Setting | Default |
|---|---|
| Keep across servers | On |

Leaving a world or switching servers no longer clears chat. Pressing **F3 + D** still clears it.

## Other chat history mods

If MoreChatHistory, Chat Patches, No Chat Reset or Don't Clear Chat History is installed, P-LUMA's history
features step aside and that mod handles them. Search keeps working.
