# VariableTest
Variable Test Application: Shows the content of a variable
Visual Basic 2005.NET:

Public Class VariableTest

    Private Sub Label2_Click(ByVal sender As System.Object, ByVal e As System.EventArgs)

    End Sub

    Private Sub BtnVariableTest_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles BtnVariableTest.Click
        Dim LastName As String

        LastName = "Luther"
        Label1.Text = LastName

        LastName = "Bodenstein von Karlstadt"
        Label2.Text = LastName


    End Sub

    Private Sub BtnVariableTest2_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles BtnVariableTest2.Click
        End
    End Sub
End Class
