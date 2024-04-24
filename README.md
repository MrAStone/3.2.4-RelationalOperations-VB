<pre lang=vb.net>
Module Module1

    Sub Main()
        ' Equal to
        Dim a As Integer = 1
        If a = 1 Then
            Console.WriteLine("Equal to")
        End If

        ' Not equal to
        If a <> 1 Then
            Console.WriteLine("Not equal to")
        End If

        ' less than
        If a < 1 Then
            Console.WriteLine("Less than")
        End If

        ' greater than
        If a > 1 Then
            Console.WriteLine("Greater than")
        End If

        ' less than or equal to
        If a <= 1 Then
            Console.WriteLine("Less than or equal to")
        End If

        ' greater than or equal to
        If a >= 1 Then
            Console.WriteLine("Greater than or equal to")
        End If


    End Sub

End Module
