# File Writing Steering

When during a certain task you require to create a temporally file that you plan to remove later. Use `/tmp` folder. Do not create temporally files on cwd or `~/` path.

```sh
cat > /tmp/<file-name> << 'EOF'
Whatever
EOF
```

This applies to any file type and any context where the user wants to review or edit a file interactively.
