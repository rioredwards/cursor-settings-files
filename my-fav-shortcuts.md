# Useful Keyboard Shortcuts

## Navigation & Search

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

### Toggle Editor Group Sizes
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.action.toggleEditorWidths"
}

### Maximize Editor Group & Hide Sidebars
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.action.maximizeEditorHideSidebar"
}

### Toggle Vertical/Horizontal Editor Group Layout
{
  "key": "ctrl+cmd+3",
  "command": "workbench.action.toggleEditorGroupLayout"
}

### Close All Editor Groups
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.action.closeAllGroups"
}

### Close All Editors in Group
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.action.closeEditorsInGroup"
}

### Close Other Editors in Group
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.action.closeOtherEditors"
}

### Close Editors in Other Groups
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.action.closeEditorsInOtherGroups"
}

### Focus Active Editor Group
{
  "key": "cmd+j",
  "command": "workbench.action.focusActiveEditorGroup",
  "when": "terminalFocus"
}

### Focus Next Tab
{
  "key": "cmd+2",
  "command": "workbench.action.nextEditorInGroup"
}

### Focus Previous Tab
{
  "key": "cmd+1",
  "command": "workbench.action.previousEditorInGroup"
}

### Focus Next Editor Group
{
  "key": "shift+cmd+3",
  "command": "workbench.action.focusNextGroup"
}

### Move Editor Left
{
  "key": "ctrl+cmd+1",
  "command": "workbench.action.moveEditorLeftInGroup"
}

### Move Editor Right
{
  "key": "ctrl+cmd+2",
  "command": "workbench.action.moveEditorRightInGroup"
}

### Move Editor to Previous Group
{
  "key": "shift+cmd+1",
  "command": "workbench.action.moveEditorToPreviousGroup"
}

### Move Editor to Next Group
{
  "key": "shift+cmd+2",
  "command": "workbench.action.moveEditorToNextGroup"
}

### Toggle Split Editor in Group
{
  "key": "ctrl+alt+cmd+0",
  "command": "workbench.action.toggleSplitEditorInGroup"
}

### Expand Editor Group
{
  "key": "ctrl+shift+alt+cmd+0",
  "command": "workbench.action.minimizeOtherEditors"
}

### Open Recently Used Tab
{
  "key": "cmd+3",
  "command": "workbench.action.quickOpenPreviousRecentlyUsedEditorInGroup",
  "when": "!activeEditorGroupEmpty"
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

### Open Git View (Primary Sidebar)
{
  "key": "shift+cmd+g",
  "command": "workbench.view.scm",
  "when": "workbench.scm.active"
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

## AI & IntelliSense

### IntelliSense: Trigger Suggest 
{
  "key": "shift+alt+s",
  "command": "editor.action.triggerSuggest",
  "when": "editorHasCompletionItemProvider && textInputFocus && !editorReadonly"
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
  "key": "ctrl+shift+alt+cmd+\\",
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
