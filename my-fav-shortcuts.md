# Useful Keyboard Shortcuts

## Editor Group Management
(Right hand alt key shortcuts)
### Top Row: Layout Actions
- alt+[ Move Editor into Previous Group
- alt+] Move Editor into Next Group
- alt+\ Join Editor Group with Next Group
- alt+shift+[ Toggle Split Editor in Group
- alt+shift+] Toggle Layout of Split Editor in Group
- alt+shift+\ Close All Editors in Group
### Middle Row: Move Focus and Tabs
- alt+; Toggle Maximize Editor Group
- alt+' Focus Next Editor Group
- alt+shift+; Maximize Editor Group and Hide Side Bars
- alt+shift+' Toggle Layout

## Navigation & Search Code & Files

### Edit Locations

{
"key": "alt+a",
"command": "workbench.action.navigateBackInEditLocations"
}
{
"key": "alt+s",
"command": "workbench.action.navigateForwardInEditLocations"
}
{
"key": "alt+x",
"command": "workbench.action.navigatePreviousInEditLocations"
}

### Search Symbols in Current File

{
"key": "cmd+t",
"command": "workbench.action.gotoSymbol",
"when": "!accessibilityHelpIsShown && !accessibleViewIsShown"
}

### Search Symbols in Workspace

{
  "key": "cmd+d",
  "command": "workbench.action.showAllSymbols"
}


### Quick Open (search files, symbols, etc...)

{
"key": "alt+w",
"command": "workbench.action.quickOpen"
}
{
"key": "alt+w",
"command": "workbench.action.quickOpenSelectNext",
"when": "inQuickOpen"
}

### Show All Editors by Most Recently Used
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.action.showAllEditorsByMostRecentlyUsed"
}

### Breadcrumbs (browse files, symbols, etc...

{
"key": "shift+cmd+.",
"command": "breadcrumbs.focusAndSelect",
"when": "breadcrumbsPossible && breadcrumbsVisible"
}

### Open Recent (browse recent windows/workspaces)

{
"key": "alt+r",
"command": "workbench.action.openRecent"
}
{
"key": "alt+r",
"command": "workbench.action.quickOpenNavigateNextInRecentFilesPicker",
"when": "inQuickOpen && inRecentFilesPicker"
}

### Find (search text in current file)

{
  "key": "cmd+f",
  "command": "actions.find",
  "when": "activeEditorIsReviewChanges || editorFocus || activeEditorIsReviewChanges && editorFocus || activeEditorIsReviewChanges && editorIsOpen || editorFocus && editorIsOpen"
}
{
  "key": "cmd+enter",
  "command": "search.action.openInEditor",
  "when": "hasSearchResult && searchViewletFocus"
}

### Find in Files (search text in all files)

{
  "key": "shift+cmd+f",
  "command": "workbench.action.findInFiles"
}

### Tree view:
{
  "key": "cmd+f",
  "command": "search.action.viewAsTree",
  "when": "hasSearchResult && searchViewletFocus"
}

### Find Previous Match
{
  "key": "ctrl+shift+alt+cmd+left",
  "command": "editor.action.previousMatchFindAction",
  "when": "editorFocus"
}

### Find Next Match

{
  "key": "ctrl+shift+alt+cmd+right",
  "command": "editor.action.nextMatchFindAction",
  "when": "editorFocus"
}

### Peek References
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "editor.action.referenceSearch.trigger"
}

### Go To Definition
{
  "key": "alt+d",
  "command": "editor.action.revealDefinition",
  "when": "editorHasDefinitionProvider && editorTextFocus"
}


## View/Window Management

### Toggle Primary Sidebar

{
"key": "alt+t",
"command": "workbench.action.toggleSidebarVisibility"
}

### Toggle Auxiliary Bar

{
"key": "alt+y",
"command": "workbench.action.toggleAuxiliaryBar"
}

### Toggle Panel (bottom)

{
  "key": "cmd+h",
  "command": "workbench.action.togglePanel"
}

### Focus Terminal

{
  "key": "cmd+j",
  "command": "workbench.action.terminal.focus",
  "when": "!terminalFocus"
}

### Resize Terminal Pane Down
{
  "key": "ctrl+shift+alt+cmd+down",
  "command": "workbench.action.terminal.resizePaneDown",
  "when": "terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
}

### Resize Terminal Pane Up
{
  "key": "ctrl+shift+alt+cmd+up",
  "command": "workbench.action.terminal.resizePaneUp",
  "when": "terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported"
}

### Toggle Maximized Panel
{
  "key": "cmd+shift+h",
  "command": "workbench.action.toggleMaximizedPanel",
}

### Toggle Agent/Editor Layout
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "cursor.toggleAgentWindowIDEUnification",
  "when": "cursor.agentIdeUnification.featureGate && workbenchState != 'empty'"
}

### Open Explorer View (Primary Sidebar)
{
  "key": "shift+cmd+e",
  "command": "workbench.view.explorer",
  "when": "viewContainer.workbench.view.explorer.enabled"
}

### Open Next View in View Picker
{
  "key": "ctrl+q",
  "command": "workbench.action.quickOpenView"
}
{
  "key": "ctrl+q",
  "command": "workbench.action.quickOpenNavigateNextInViewPicker",
  "when": "inQuickOpen && inViewsPicker"
}

### Open Search View (Primary Sidebar)
{
  "key": "shift+cmd+f",
  "command": "workbench.view.search",
  "when": "viewContainer.workbench.view.search.enabled"
}

### Open Git View (Primary Sidebar)
{
  "key": "shift+cmd+g",
  "command": "workbench.view.scm",
  "when": "workbench.scm.active"
}

### Open Debug View (Primary Sidebar)
{
  "key": "shift+cmd+d",
  "command": "workbench.view.debug",
  "when": "viewContainer.workbench.view.debug.enabled"
}

### Open Extensions View (Primary Sidebar)
{
  "key": "shift+cmd+x",
  "command": "workbench.view.extensions",
  "when": "viewContainer.workbench.view.extensions.enabled"
}

### Open Browser Tab
{
  "key": "shift+cmd+b",
  "command": "composer.toggleBrowserTab"
}

### Reopen Closed Editor
{
  "key": "shift+cmd+t",
  "command": "workbench.action.reopenClosedEditor"
}

### Open Settings

{
  "key": "cmd+,",
  "command": "workbench.action.openSettings"
}

### Open Keyboard Shortcuts
{
  "key": "shift+alt+k",
  "command": "workbench.action.openGlobalKeybindings"
}

### Split Editor
{
  "key": "ctrl+\\",
  "command": "workbench.action.splitEditor"
}

## Commands

### Command Palette

{
"key": "shift+alt+e",
"command": "workbench.action.showCommands"
}

### Reload Window
{
  "key": "alt+cmd+r ctrl+cmd+r",
  "command": "workbench.action.reloadWindow",
  "when": "false"
}

### Run Task
{
  "key": "shift+alt+z",
  "command": "workbench.action.tasks.runTask"
}

### Open Color Picker
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "editor.action.showOrFocusStandaloneColorPicker"
}

## AI & IntelliSense

### IntelliSense: Trigger Suggest 
{
  "key": "cmd+i",
  "command": "editor.action.triggerSuggest",
  "when": "editorHasCompletionItemProvider && textInputFocus && !editorReadonly && !suggestWidgetVisible"
}

### CursorAI: Generate Inline Edits or Question
{
  "key": "cmd+k",
  "command": "aipopup.action.modal.generate",
  "when": "editorFocus && !composerBarIsVisible"
}

### CursorAI: Send to Agent & New Chat
{
  "key": "cmd+l",
  "command": "composer.sendToAgent",
  "when": "editorHasPromptBar && editorPromptBarFocused"
}
{
  "key": "cmd+l",
  "command": "aichat.newchataction"
}

### CursorAI: Previous Chat Tab
{
  "key": "cmd+[",
  "command": "composer.previousChatTab",
  "when": "composerFocused && !editorTextFocus"
}

### CursorAI: Next Chat Tab
{
  "key": "cmd+]",
  "command": "composer.nextChatTab",
  "when": "composerFocused && !editorTextFocus"
}

### Show Snippets
{
  "key": "shift+alt+a",
  "command": "editor.action.showSnippets"
}

### Hide Inline Suggestion
{
    "key": "ctrl+shift+alt+cmd+space",
    "command": "editor.action.inlineSuggest.hide",
    "when": "inlineSuggestionVisible"
}

### Toggle Cursor Tab
{
  "key": "ctrl+shift+alt+cmd+g",
  "command": "editor.cpp.toggle"
}

### CursorAI: Accept Next Word of Inline Suggestion
{
  "key": "cmd+right",
  "command": "editor.action.inlineSuggest.acceptNextWord",
  "when": "cppSuggestion && !editorReadonly || inlineSuggestionVisible && !editorReadonly"
}

### CursorAI: Start Voice Chat
{
  "key": "shift+cmd+b",
  "command": "workbench.action.chat.startVoiceChat",
  "when": "chatIsEnabled && hasSpeechProvider && inChatInput && !chatSessionRequestInProgress && !editorFocus && !notebookEditorFocused && !scopedVoiceChatGettingReady && !speechToTextInProgress || chatIsEnabled && hasSpeechProvider && inlineChatFocused && !chatSessionRequestInProgress && !editorFocus && !notebookEditorFocused && !scopedVoiceChatGettingReady && !speechToTextInProgress"
}

### Open Quick Fix
{
  "key": "ctrl+.",
  "command": "editor.action.quickFix",
  "when": "editorHasCodeActionsProvider && textInputFocus && !editorReadonly"
}

### Auto Fix Quick Fix
{
  "key": "alt+cmd+.",
  "command": "editor.action.autoFix",
  "when": "textInputFocus && !editorReadonly && supportedCodeAction =~ /(\\s|^)quickfix\\b/"
}



## Folding & Code View Actions

### Fold All
{
  "key": "ctrl+shift+alt+cmd+-",
  "command": "editor.foldAll",
  "when": "editorTextFocus && foldingEnabled"
}

### Unfold All
{
  "key": "ctrl+shift+alt+cmd+=",
  "command": "editor.unfoldAll",
  "when": "editorTextFocus && foldingEnabled"
}

### Toggle Fold Recursively
{
  "key": "cmd+r shift+cmd+l",
  "command": "editor.toggleFoldRecursively",
  "when": "editorTextFocus && foldingEnabled"
}

### Toggle Import Fold
{
  "key": "",
  "command": "editor.toggleImportFold"
}


### Tailwind Fold: Toggle
{
  "key": "ctrl+alt+a",
  "command": "tailwind-fold.toggleAutoFold"
}

### Toggle Word Wrap
{
  "key": "alt+z",
  "command": "editor.action.toggleWordWrap"
}

### Toggle Zen Mode
{
    "key": "ctrl+shift+alt+cmd+z",
    "command": "workbench.action.toggleZenMode"
}

### Zoom In
{
  "key": "cmd+=",
  "command": "workbench.action.zoomIn"
}

### Zoom Out
{
  "key": "cmd+-",
  "command": "workbench.action.zoomOut"
}

### Increase Font Size
{
  "key": "alt+=",
  "command": "editor.action.fontZoomIn"
}

### Decrease Font Size
{
  "key": "alt+-",
  "command": "editor.action.fontZoomOut"
}


## Selection & Multi-cursor

### Select All Occurrences
{
  "key": "shift+cmd+a",
  "command": "editor.action.selectHighlights",
  "when": "editorFocus"
}

### Add Next Occurrence
{
  "key": "shift+cmd+s",
  "command": "editor.action.addSelectionToNextFindMatch",
  "when": "editorFocus"
}

### Find Next Occurrence
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "editor.action.nextSelectionMatchFindAction",
  "when": "editorFocus"
}

### Find Previous Occurrence
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "editor.action.previousSelectionMatchFindAction",
  "when": "editorFocus"
}

### Shrink Selection

{
  "key": "ctrl+shift+alt+cmd+d",
  "command": "editor.action.smartSelect.shrink",
  "when": "editorTextFocus"
}

### Expand Selection

{
  "key": "ctrl+shift+alt+cmd+f",
  "command": "editor.action.smartSelect.expand",
  "when": "editorTextFocus"
}

## Editor

### Rename Symbol
{
  "key": "cmd+r",
  "command": "editor.action.rename",
  "when": "editorHasRenameProvider && editorTextFocus && !editorReadonly"
}

### Delete Line
{
  "key": "cmd+backspace",
  "command": "editor.action.deleteLines",
  "when": "textInputFocus && !editorReadonly"
}

### Outdent Lines
{
  "key": "cmd+[",
  "command": "-editor.action.outdentLines",
  "when": "editorTextFocus && !editorReadonly"
}

### Indent Lines
{
  "key": "cmd+]",
  "command": "-editor.action.indentLines",
  "when": "editorTextFocus && !editorReadonly"
}

### Join Lines
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "editor.action.joinLines",
  "when": "editorTextFocus && !editorReadonly"
}

## Terminal

### Clear Console
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.debug.panel.action.clearReplAction",
  "when": "focusedView == 'workbench.panel.repl.view'"
}

### CursorAI: Generate in Terminal
{
  "key": "cmd+k",
  "command": "cursorai.action.generateInTerminal",
  "when": "terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported || terminalHasBeenCreated && terminalPromptBarVisible || terminalProcessSupported && terminalPromptBarVisible"
}

### Split Terminal
{
  "key": "cmd+\\",
  "command": "workbench.action.terminal.split",
  "when": "terminalFocus && terminalProcessSupported || terminalFocus && terminalWebExtensionContributedProfile"
}

## Git Stuff

### Open Local File History Picker
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.action.localHistory.restoreViaPicker"
}
