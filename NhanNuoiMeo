import streamlit as st
St=st.set_page_config(page_title="hoc python", page_icon="meo.ico")

st.balloons()


app_mode=st.sidebar.selectbox("Hau Cung", ['Home','Beo', "Gay"])

if app_mode=="Home":
    St=st.header("Noi cho nhan nuoi meo")
    St=st.header("[Neu ban muon nhan nuoi meo hay dien vao link sau](https://forms.gle/TJ3CpfhaBQzj6LeX8) ")

elif app_mode=="Beo":
    St=st.title("Meo Beo")
    St=st.image("hinh_anh_meo_u1.jpg", width=300, caption="Em meo 20 kg")
    St=st.video("meo_beo.mp4")
    St=st.write("Meo beo thich ngu")
    f=open("meo_beo.mp4","rb")
    St=st.download_button(label="tai video meo", data=f, file_name="meo_beo.mp4")
elif app_mode=="Gay":
    St=st.title("Meo Gay")
    St=st.image("Bat-Cuoi-Truoc-Loat-.png", width=300)
    St=st.video("loi nho.mp4")
