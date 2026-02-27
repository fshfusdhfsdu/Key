# BK

## User Interface

### Window System

- Splash Screen
- Topbar
- Workspaces
    - !Previous/Next Workspace
    
    → Properties Editor, Tool tab, Workspace
    
    - Pin Scene
    - Mode
    - Sequencer Scene
    - Sync Scene Time
    - Filter Add-ons
- Status Bar
- Areas
    - !Maximize Area
    - !Focus Mode
- Regions
    - !Sidebar
- Tabs & Panels

### Keymap

### UI Elements

### Tools & Operators

- Tool System
    - !Toolbar
    - !Pop-Up Toolbar
    - !Quick Favorites
    - Properties of Tools
- Operators
    - !Menu Search
- Undo & Redo
    - !Undo
    - !Redo
    - !Adjust Last Operation
    - Undo History
    - !Repeat Last
    - Repeat History
- Annotations
    - Color
    - Annotation Layer
    - Placement
    - Stabilize Stroke
- Selecting
    - Tweak
    - !Box Select
    - !Circle Select
    - !Lasso Select

### Nodes

…

## Editor

### 3D Viewport

- Object Modes
    - !Switching Modes
    - !Switching Objects
    - Multi-Object Editing
- Navigating
    - Navigation Gizmo
    - !Orbit
    - !Roll
    - !Pan
    - Zoom In/Out
    - !Zoom Region
    - !Dolly View
    - !Frame All
    - !Frame Selected/Last Stroke
    - !Fly/Walk
    - Fly/Walk Positioning a camera
    - Fly/Walk Recording camera movement
    
    → View, Align View
    
    - !Align Active Camera to View
    - Align Active Camera to Selected
    - !Center Cursor and Frame All
    - Center View to Cursor
    - View Lock to Active
    - View Lock Clear
    - !Perspective/Orthographic
    - !Toggle Local View
    - !Remove from Local View
    - !Viewing the Active Camera
    - !Setting the Active Camera
    - Zoom Camera 1:1
    - !Clipping Region
    - !Render Region
    - !Quad View
- Controls
    - !Transform Orientation
    - Custom Orientations
    - !Transform Pivot Point
    - !Snapping
    - !Snapping Setting
    - !Proportional Editing
    - !Proportional Falloff
    - !Proportional Connected Only
    - !Proportional Projected from View
- Display
    - Object Type Visibility
    - Gizmos
    - Viewport Overlays
    - !Viewport Shading

## Scene & Object

### Scenes

- Scene Properties
    - Camera
    - Background Scene
    - Active Clip
    - Unit
    - Gravity
    - ~Keying Sets
    - Audio
    - ~Rigid Body World
    - ~Animation
    - Custom Properties

### Objects

- Select
    - !All
    - !None
    - !Invert
    - !Box Select
    - !Circle Select
    - !Lasso Select
    - Select Active Camera
    - Select Mirror
    - Select Random
    - !Select More/Less
    - Select All by Type
    - !Select Grouped
    - !Select Linked
    - Select Pattern
- Editing
    - !Next/Previous Component
    - !Mirror
    - !Clear
    - !Apply
    - !Duplicate Linked
    - !Join
    - !Make Parent
    - !Clear Parent
    - ~Constraints & Track
    - Rigid Body
    - Convert
    - Show/Hide
    - ~Clean Up
    - !Delete Globally
- Tool
    - Scale Cage

# RK

## Language

- Common
    - immutable/mutable variables
    - declaring constants
    - shadowing
    - four primary scalar types (i, f, b, c)
    - two primary compound types (t, a)
    - parameters & arguments
    - statements & expressions
    - return value
    - if expressions
    - loop expressions
    - loop labels
    - while
    - for in
    
- Ownership
    - rules of ownership
    - rules of references
    - slice
- Structs
    - defining
    - instantiating
    - field init
    - update syntax
    - tuple structs
    - unit-like structs
    - drive trait: Debug
    - {:?} & {:#?}
    - dbg!
    - method syntax
    - self & Self
- Enums
    - defining
    - Option enum
    - match expression
    - patterns that bind to values
    - _
    - if let
- Packages, Crates, and Modules
    - binary/library crate
    - crate root
    - src/bin
    - mod, pub, use
    - absolute/relative path
    - access between child modules and parent modules
    - access brothers’ modules
    - pub struct/enum
    - Idiomatic use Paths
    - as
    - Re-exporting Names with pub use
    - Nested Paths
- Error Handling
    - panic, Unwinding & aborting
- Generic Types, Traits and Lifetimes
    - default implementations
    - traits as parameters
    - trait bound
    - multiple trait bounds
    - where
    - returning types that implement traits
    - Using Trait Bounds to Conditionally Implement Methods
    - Lifetime in Functions
    - Lifetime in struct
    - three rules
    - Lifetime in Method Definitions
    - static Lifetime
- Automated Test
    - #[test]  **&**  #[cfg(test)]
    - assert!
    - #[should_panic]
    - #[should_panic(expected = “*”)]
    - Result
    - test thread count
    - —show-output
    - single test
    - Filtering multiple test
    - #[ignore]
- Iterators and Closures
    - closure
    - capturing reference
    - Moving Ownership
    - consuming adapters
    - 

## standard Libs

### Prelude

- std::marker::{Sized, Copy, Send, Sync, Unpin}
    - Copy & operator=
    - difference between Copy & Clone
- std::ops::{FnOnce, FnMut,Fn , AsyncFn, AsyncMut, AsyncOnce}

## syntactic sugar

- Iterator & for in
