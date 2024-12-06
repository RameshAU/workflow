## Command to trigger the workflow with repository dispatch - webhook event
> curl -X POST \
>-H "Accept: application/vnd.github+json" \
>-H "Authorization: token <personal access token>" \
>-d '{"event_type": "webhook", "client_payload": {"key": "value"} }' \
>https://api.github.com/repos/RameshAU/workflow/dispatches
## Below link is the example contexts which can be used in the code
> <script src="https://gist.github.com/colbyfayock/1710edb9f47ceda0569844f791403e7e.js"></script>