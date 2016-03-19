using Microsoft.AspNet.Identity.EntityFramework;
using System;
using System.Collections.Generic;
using System.ComponentModel.DataAnnotations;
using System.Linq;
using System.Web;

namespace Demo_NMM.EF.D2.Models
{
    public class NMMUser : IdentityUser
    {
        [Required(ErrorMessage = "{0} is required.")]
        [StringLength(50)]
        public string City { get; set; }
    }
}