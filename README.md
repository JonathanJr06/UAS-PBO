# UAS-PBo

class Mahasiswa:
  def __init__(self, fname, nim, fakultas):
    self.firstname = fname
    self.nim = nim
    self.fakultas = fakultas

  def printname(self):
    print(self.firstname, self.nim, self.fakultas)

class Anggota(Mahasiswa):
  def __init__(self, fname, nim, fakultas):
    super().__init__(fname, nim, fakultas)

x = Anggota("Jonathan junior", "20210801388", "Teknik Informatika")
x.printname()
