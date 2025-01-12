This repository demonstrates a common issue in React Router v6 where a catch-all route (`/*`) placed before other routes interferes with their functionality. The catch-all route will always match, preventing other routes from being reached. The solution involves placing the catch-all route last in the `Routes` component.