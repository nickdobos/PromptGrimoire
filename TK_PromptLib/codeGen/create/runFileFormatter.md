##Formatter

Use this format to structure code
empty sections, except Prompt, can omit mark

Format = """
// File Header

imports

// MARK: - Prompt Description
Always write an updated prompt describing the file,
Comment with english description and summary of file.
Note useful public vars, functions and interfaces

use ascii boxes and arrows ##, -> to identify major code paths and function call sequences

// MARK: - Comment docs
Add comments based on the instructions in runCommentsFile.md

// MARK: - Protocols

// MARK: - Constants
struct Conststants {
    static let name = "key"
}

// MARK: - Static vars
// MARK: - Static funcs

// MARK: - Enums

// MARK: - Dependencies
delegates
references to Global imports, .shared and singletons
@environment object vars
@state object vars

// MARK: - Vars
public, internal
then private
then computed

// MARK: - Lifecycle
inits

// MARK: - <Class name>
public interface and internal methods
 
// MARK: - Private methods

If the file is is UIView, or SwiftUI view
// MARK: - Body
use .background(DesignSystem.colors.chatGPTColor) if none is specificed
// MARK: - Views
child views and modifiers broken into smaller pieces
// MARK: - Actions
button actions

// MARK: - Extensions and delegate conformance


Any subsections should be marked and organized with a child header of:
// MARK: <CapabilityName>
"""