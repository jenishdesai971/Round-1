# Round-1-Task
Assignment: "The Floating Hero Section"
Objective Replicate the "Legal Work Platform" hero section shown in the design screenshot as closely as possible using Next.js.

Design Assets

  Reference Image: <img width="1440" height="862" alt="Chota Landing Page" src="https://github.com/user-attachments/assets/8d6f8977-f434-47bf-bb99-7fe66b72758c" />

  Icons: Use an icon library like lucide-react or heroicons (e.g., Gavel for "Matters", FileText for "Documents", CheckSquare for "Tasks").

  Font: Use a standard geometric sans-serif font (e.g., Inter or Plus Jakarta Sans from Google Fonts).

Core Requirements
  The Layout (CSS Mastery)

    Implement the split layout: Text content on the left, "floating elements" visualization on the right.

    The "pills" (Billing, Matters, Tasks, etc.) must be positioned and rotated to match the visual "chaotic but organized" aesthetic.

    Constraint: The layout must be responsive. On mobile devices, the floating elements should either stack gracefully or be hidden/simplified.

Component Architecture

  Create a reusable FloatingCard component. It should accept props for:

    color (Blue, Orange, Dark, etc.)

    rotation (The angle of the card)

    icon and label

The "John Doe - Portal" card is unique. The candidate should demonstrate how they handle a "variant" or a specific slot within their component structure to accommodate this different layout.

Visual Polish

  Implement the blurred background shapes (the light blue blobs behind the content).

Match the typography hierarchy (H1 vs. subtext).

Technical Stack
  Framework: Next.js 14+ (App Router).

  Styling: Tailwind CSS is preferred (to see how they handle arbitrary values like rotate-[12deg]), but CSS Modules are acceptable.
