# Tailwind CSS Shadow Utility Issue

This repository demonstrates a common issue encountered when using Tailwind CSS's shadow utilities.  Specifically, the `shadow-lg` class fails to produce the expected shadow effect.

The problem is likely due to incorrect configuration or conflicts with other CSS stylesheets.  The solution involves verifying Tailwind's configuration and ensuring no conflicting styles are overriding the shadow utility.

## Bug Report

The provided `bug.html` file showcases the problem. Despite applying the `shadow-lg` class, no shadow is visible. Other Tailwind classes are rendering correctly, indicating the issue is specific to the shadow utility.

## Solution

The `bugSolution.html` file presents a working solution, focusing on verifying Tailwind's configuration and resolving any potential conflicts.