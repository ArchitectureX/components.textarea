# @architecturex/components.textarea

## TextArea

This is a simple React TypeScript component for a textarea form element styled with Tailwind CSS.

### Installation

`npm install @architecturex/components.textarea`

### Usage

```javascript
import TextArea from '@architecturex/components.textarea'

const App: React.FC = () => {
  return (
    <div className="container mx-auto p-4">
      <h1 className="text-2xl font-bold mb-4">React TypeScript Tailwind TextArea Component</h1>
      <form>
        <TextArea label="Enter your message:" rows={5} placeholder="Type here..." />
        {/* Add other form elements or submit button if needed */}
      </form>
    </div>
  );
};

export default App;

```

### Contribution

Feel free to suggest improvements, report issues, or contribute to enhancing these utilities. Your feedback and contributions are welcome!
