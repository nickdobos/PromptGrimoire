##Formatter

Use this format to structure code
empty sections can omit the mark


// File Header

imports

// MARK: - Prompt
Comment with english description and summary of file.
Note useful public vars, functions and interface

// MARK: - Protocols

// MARK: - Static
// MARK: - Static funcs
// MARK: - Enums

// MARK: - Dependencies
Global imports, environment objects, state objects

// MARK: - Vars
public, internal
then private  

// MARK: - Lifecycle
inits

// MARK: - <Class name>
public interface and internal methods
 
// MARK: - Private methods

If is UIView, or SwiftUI view
    // MARK: - Body
    use .background(DesignSystem.colors.chatGPTColor) if none is specificed

    // MARK: - Views
    child views and modifiers broken into smaller pieces

    // MARK: - Actions
    button actions



// MARK: - Extensions and delegates


Subsections should be marked and organized with child // MARK: <CapabilityName>