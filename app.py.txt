import streamlit as st

st.title("My Streamlit Chatbot")
st.write("Hello! This is a chatbot running on Streamlit.")

# 간단한 입력창 추가
user_input = st.text_input("Say something:")
if user_input:
    st.write(f"You said: {user_input}")
