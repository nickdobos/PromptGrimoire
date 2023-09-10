##Formatter

Use this format to structure code
empty sections can omit the mark

Format = """
// File Header

imports

// MARK: - Prompt
Comment with english description and summary of file.
Note useful public vars, functions and interface

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
Global imports
@environment objects
@state objects

// MARK: - Vars
public, internal
then private  

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

Subsections should be marked and organized with a child header of:
// MARK: <CapabilityName>

"""