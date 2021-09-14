# Hi
# Run the app
if __name__ == '__main__':
    # REVIEW8: Adding dev_tools_ui=False, dev_tools_props_check=False can prevent error appearing before calling callback function
    app.run_server(mode="inline", host="localhost", debug=False, dev_tools_ui=False, dev_tools_props_check=False)
